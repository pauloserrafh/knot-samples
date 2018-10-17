# KNoT platform samples

This repository contains examples for KNoT usage.
You can use it as an starting point to create your customized app to interact
with your KNoT Things.

Each example must be compliant with the following path architecture:

| example_name/\
|-- cloud/\
|-- device/

The cloud folder contains the necessary files to run the example in the web
environment.
If necessary, have subfolders for frontend and backend separately.

| cloud/\
|-- backend/\
|-- frontend/

The device folder contains the code samples for KNoT Things. Or should point
to the proper repository containing the example. Create a subfolder for each
device.

| device/\
|-- arduino/\
|-- zephyr/

To start using the KNoT platform, check the [KNoT User Guide](http://knot-devel.cesar.org.br/resources/knot_users_guide.pdf).