### This repo will simluate traffic to a designated website.

Before you start, be sure you have python installed in your env.

Then you will want to install locust & forever

`pip3 install locust`

`pip3 install forever`

once installed, located your locustfiles in the load_generation directory.

You will need to update the HOST value in locust.conf to point to the website where you would like to simulate traffic. 
If you are hosting locally, make sure this repo is on the same host.

Once updated, run the following command:

`nohup locust &`
