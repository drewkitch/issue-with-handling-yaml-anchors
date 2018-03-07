# Issue with handling of YAML anchors

1. Check the YAML loaded file -- `ruby -e "require 'pp'; require 'yaml'; pp(YAML.load_file('codeship-services.yml'))"`
2. Current services validation error on Codeship Pro `services file error: both dockerfile and dockerfile_path are specified. Please specify one or the other` 
