Ref:http://catchmecode.com/blog/2013/08/01/jetty-multiple-instances/
Note: that is for jetty 9. Due to the fact that jetty9 can only run in JDK7, I have to work out a sample of JDK6, os I use jetty 8 .
1) make sure wipe out the jetty.xml and webdefault.xml in jetty root.
2) copy the dev and stage folder into webapps in the jetty root.
Then run start_jetty_stage.sh and see: http://localhost:8880/
Or run start_jetty_dev.sh and see:http://localhost:8881/
