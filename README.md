# Snappy-Chroot-Frontend
A chroot container for the Snappy Frontend

Unpack the tar.gz file:  
  cd /  
  tar xzvf snappy-fe-chroot-vx.y.z.tgz   

Before starting two things need to be done:  

1) Fill out the environment variables:  
  /srv/snappyfe/bin/edit_env_vars  
  
2) Add sources, targets and tenents:  
  /srv/snappyfe/bin/edit_tables  


To start the Frontend service: /srv/snappyfe/bin/start [port_number]  
To stop the Frontend service: /srv/snappyfe/bin/stop  

By default the Frontend will run on port 8080
