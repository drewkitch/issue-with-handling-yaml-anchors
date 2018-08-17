# Issue with handling of YAML anchors

1. Check the YAML loaded file -- `ruby -e "require 'pp'; require 'yaml'; pp(YAML.load_file('codeship-services.yml'))"`
2. Current services validation error on Codeship Pro `services file error: both dockerfile and dockerfile_path are specified. Please specify one or the other` 


Issue Resolved? --> [ ![Codeship Status for drewkitch/issue-with-handling-yaml-anchors](https://app.codeship.com/projects/9a307530-048c-0136-0999-0e7fdaa29a0c/status?branch=master)](https://app.codeship.com/projects/280510)

2018-8-17 checkup
