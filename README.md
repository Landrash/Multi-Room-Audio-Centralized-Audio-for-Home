# Wireless Multi-Room Audio System For Home
Welcome, This Github Repository will provide you all the details about setting up a centralized audio system for your home using ONLY Raspberry Pi's and Old Speakers

I have always wanted to have a centralized audio system for my home, since my home is not currently wired for that, I decided to maky my own centralized audio system using nothing but Raspberry Pi's and some {cheap} bluetooth speakers from amazon and leverage any old speakers lying at home that can be plugged into a 3.5mm audio jack. I documented all the steps here, for those who want to do the same.

I use Mopidy, Snapcast server and client software(s) to achieve this functionality. The Mopidy is just a media player, and the output of the mopidy is directed to a pipe, where the Snapcast server is listening to. When any audio/music content is streamed to that pipe, Snapcast server receives the media, and broascasts to all of it's clients (snapcast clients).

The ideal set up would be to install Mopidy, Snapcast Server and Snapcast client on one Raspberry Pi, and use other Raspberry Pis as clients - where it will pnly have Snapclient software running on it.  

## Installing Mopidy 

## Instaling Snapcast Server

## Installing Snapcast client

## Setting up PulseAudio
