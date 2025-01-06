# Final Project Proposal

## Group Members:

Edmund Liang
       
# Intentions:

The project will be a music player with support for making playlists, and possibly having two or more computers listening to the same music simultaneously. Pausing/playing, skipping, and looping will be implemented.
    
# Intended usage:

The user interface will be in the terminal, with separate displays for when a song is playing and to create playlists.
  
# Technical Details:

A description of your technical design. This should include:

How you will be using the topics covered in class in the project.
- Allocating memory - used to create playlists
- Working with files - music files will be read, files will be created to store playlist information and later read
- Finding information about files - song name and length will be found
- Processes - forking will be used so that the music can be played while the user interacts with the UI
- Signals - the program will handle interrupt, exit, etc. signals properly so that it is done smoothly
- Shared memory & semaphores/pipes - when the song finishes playing, it will communicate with the main program for it to start the next song

What data structures you will be using and how.

What algorithms you will be using, and how.

# Intended pacing:

A timeline with expected completion dates of parts of the project.
