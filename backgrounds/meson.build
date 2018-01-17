dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)

adapta_xml = configure_file(
  input: 'adapta-backgrounds.xml.in',
  output: 'adapta-backgrounds.xml',
  configuration: dataconf
)

backgrounds = [
  'tri-fadeno.jpg',
  'tealized.jpg',
  'suna.jpg',
  'poly.jpg',
  'kahelo.jpg'
]

install_data([adapta_xml] + backgrounds, install_dir: backgrounddir)
install_data([adapta_xml], install_dir: metadatadir_gnome)
install_data([adapta_xml], install_dir: metadatadir_cinnamon)
install_data([adapta_xml], install_dir: metadatadir_mate)
