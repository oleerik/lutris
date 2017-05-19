datadir = get_option('datadir')
appdatadir = join_paths(datadir, 'appdata')
desktopdir = join_paths(datadir, 'applications')
polkitdir = join_paths(datadir, 'polkit-1/actions')
icondir = join_paths(datadir, 'icons/hicolor')

install_subdir('lutris', install_dir: datadir)
install_data('appdata/lutris.appdata.xml', install_dir: appdatadir)
install_data('applications/lutris.desktop', install_dir: desktopdir)
install_data(
  'polkit-1/actions/net.lutris.resetxpad.policy',
  'polkit-1/actions/net.lutris.xboxdrv.policy',
  'polkit-1/actions/net.lutris.xboxdrvctl.policy',
  install_dir: polkitdir
)
install_data('icons/hicolor/48x48/apps/lutris.png',
  install_dir: join_paths(icondir, '48x48/apps')
)
install_data('icons/hicolor/scalable/apps/lutris.svg',
  install_dir: join_paths(icondir, 'scalable/apps')
)
