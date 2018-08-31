genrule(
  name = 'core-foundation-framework', 
  out = 'CoreFoundation.framework', 
  cmd = 'cp -r /System/Library/Frameworks/CoreFoundation.framework $OUT', 
)

prebuilt_apple_framework(
  name = 'core-foundation', 
  framework = ':core-foundation-framework', 
  preferred_linkage = 'static', 
  visibility = [
    'PUBLIC', 
  ], 
)
