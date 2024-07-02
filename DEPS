use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '5be22f98733c674d532598454ae729253bc53e82',
  'effcee_revision' : 'd74d33d93043952a99ae7cd7458baf6bc8df1da0',
  'glslang_revision': '8a5086efb01ce204a0060ae8fbe112aba935d44f',
  'googletest_revision': '34ad51b3dc4f922d8ab622491dd44fc2c39afee9',
  're2_revision': 'c9cba76063cf4235c1a15dd14a24a4ef8d623761',
  'spirv_headers_revision': 'eb49bb7b1136298b77945c52b4bbbc433f7885de',
  'spirv_tools_revision': 'ce46482db7ab3ea9c52fce832d27ca40b14f8e87',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
