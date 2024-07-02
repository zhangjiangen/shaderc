use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '5be22f98733c674d532598454ae729253bc53e82',
  'effcee_revision' : 'd74d33d93043952a99ae7cd7458baf6bc8df1da0',
  'glslang_revision': '8a5086efb01ce204a0060ae8fbe112aba935d44f',
  'googletest_revision': '34ad51b3dc4f922d8ab622491dd44fc2c39afee9',
  're2_revision': '6dcd83d60f7944926bfd308cc13979fc53dd69ca',
  'spirv_headers_revision': '2acb319af38d43be3ea76bfabf3998e5281d8d12',
  'spirv_tools_revision': 'c91d9ec1580dce89b10b0ca6a368800e2deaf1cb',
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
