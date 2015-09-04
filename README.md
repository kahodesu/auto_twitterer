# auto_twitterer

///////////////////////////////////////
//         AUTO TWITTERER            //
//          by Kaho Abe              //
//          Sept 4, 2015             //
///////////////////////////////////////
// Made this for games.              //
// Run this seperately to tweet as   //
// many images as possible, without  //
// shutting down.                    //
///////////////////////////////////////

gitignoring 2 things:

1. twitter4j library (download at http://twitter4j.org/en/index.html)

2. text file with secret OAuth keys

This sketch will look for the oldest image in a directory and tweet it, with the title as its text. 

Then will wait for 2 minutes to tweet the next one. 

If there aren't any images in the directory, it won't do anything except check it,

and won't tweet until there is a new image and it's been 2 minutes since the last tweet. 

Used Schiffman's Timer Class and twitter4j library.
