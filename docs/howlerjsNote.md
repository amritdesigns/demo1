Note about next lecture (Howler.js)
Hi Everyone!

Howler.js has updated their syntax in the latest version. Click here to read more about it. See below for an example of the updated syntax (hint: it uses src instead of urls as a key inside of the sound object):

var sound = new Howl({
  src: ['sound.mp3']
});
 
sound.play();
You can also copy all of the updated syntax for the keyData object from here.

You'll also need to update your Howler file, see here for a CDN link to the latest version.


Audio not playing issue:
If you get the following error in your chrome console:

The Web Audio autoplay policy will be re-enabled in Chrome 70 (October 2018). 
Please check that your website is compatible with it.
and your audio won't play, then please see here.