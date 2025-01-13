# ampy-wrapper

This is a little Python script that uses the subprocess module to make it easy to manage a Raspberry Pi Pico from the command line. Requires that the tools ampy and tio be installed and in your $PATH. It wraps all of the commands available to ampy and provides the ability to drop into your Pi's REPL with tio. 

I didn't want to mess with Thonny or whatever other graphical Pi SDKs are out there. This script is pretty barebones, but it should save you a few hours of work developing your own command line setup for Pico dev. I'm releasing it cc0, so have fun.
