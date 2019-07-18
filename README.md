# Docker Image Maintenance Page

Hi, this one page of html only show Maintenance info about the system. it's not really great and nothing special in it.

# How to Build
Open your terminal and run this command:

    docker build . t [registry]/[image_name]:[tag]

for example, my account docker hub is `fatir`and I name it `maintenance`with tag `1.0.0`, the command would be like this:

    docker build . t fatir/maintenance:1.0.0