It's happened to everyone... 
You make a few to many changes and the network isn't in a place for you to experiment/learn any more.

Here's some help to get you back on track.

We ran pb.collect.goldenconfiguration.yml and collected the configurations. I disabled it afterwards to prevent accidentally running it again.

To re-enable, remove all of the # signs at the beginning of the lines. Be careful not to add an extra space or take one away.

All you have to do to return the network to the base configuration is run ~ ansible-playbook -i all.inv pb.configure.golden.yml~. 
