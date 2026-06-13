project('boost-odeint',
  version : '1.91.0',
  meson_version: '>= 1.5.0',
)

fs = import('fs')
if not fs.exists('odeint/README.md')
  error('Missing the `boost_math` submodule! Run `git submodule update --init` to fix this.')
endif

boost_odeint_dep = declare_dependency(include_directories: 'odeint/include')
