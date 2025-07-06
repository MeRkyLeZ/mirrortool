__init__py = configure_file(
    input : '__init__.py',
    output : '__init__.py',
    configuration : conf_data
)

py.install_sources(
    [
        __init__py,
    ],
    subdir : 'mirrortool',
    pure : not native_extensions
)

subdir('util')
subdir('_lmirrordist')
