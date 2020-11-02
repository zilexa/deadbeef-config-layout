# deadbeef my config and layout, with folder tree view!

Deadbeef layout file and plugins for Ubuntu

Since it is a pain to build some of the plugins (Infobar, Musical Spectrum) and configure a nice UI, I have spend a few hours figuring it out for future use, mostly because I needed a music player with folder tree view support. For the old folks that have music collections without proper tags. 

Feel free to use it. 
copy the config file to: $HOME/.config/deadbeef/
copy the lib folder to: $HOME/.local/
start Deadbeef. 

Screenshots:

On Ubuntu Budgie 20.04.1 with standard Pocillo theme:
![Deadbeef ZileXa screenshot with Ubuntu Budgie Pocillo](https://i.ibb.co/Cb0TWZb/Screenshot-from-2020-08-08-15-22-16.png)

On Ubuntu Budgie 20.04.1 with Arc-Dark theme:
![Deadbeef ZileXa screenshot with Ubuntu Budgie Arc-Dark](https://i.ibb.co/Cb1rHsy/Screenshot-from-2020-08-08-15-24-06.png)

By default the Wave Spectrum has a white background to match the default Ubuntu Budgie Pocillo theme. To get the dark theme, you must select Arc-Dark for your system first:

1. Budgie Menu > Budgie Desktop Settings > Widgets: Select Pocillo-Dark or Arc-Dark.
2. DeadBeef > Right click the wave spectrum > Configure > Background (top right) > Custom + > fill in #383c4a and hit Tab or Enter.


Note lyrics & music info is available via the Infobar plugin, which is compiled (gtk3) and included however it crashes the whole player regularly. The last version is from 2013. I don't recommend using it but you can go to View > Design mode, add/remove UI parts to add it. 
