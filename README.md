# MP3-tag-reader
A command-line based MP3 Tag Reader and Editor developed in C to view and modify ID3 metadata stored in MP3 audio files.

**Project Overview**

The MP3 Tag Reader allows users to read and edit important metadata information from an MP3 file, such as:
Title
Artist
Album
Year
Genre
Comment
The project works with ID3 tags and provides a simple command-line interface for viewing and updating the metadata.

**Technologies Used**
Programming Language: C
Concepts: File Handling, Structures, Pointers, Command-Line Arguments
File Format: MP3

**Working**
The program accepts the MP3 filename through command-line arguments.
It opens the MP3 file in binary mode.
It checks for the ID3 header.
It reads the ID3 frames containing metadata.
The required tag information is extracted and displayed.
During editing, the selected frame is modified with the new value.
The updated information is written to an output MP3 file.

**Concepts Learned**

File handling 
Structures and pointers
Command-line arguments
String manipulation
Reading and modifying file metadata
