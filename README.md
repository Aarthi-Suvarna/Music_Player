# Music_Player
The program starts by initializing the Pygame library, specifically its mixer module, which handles audio operations. Two essential functions are defined: play_music(file_path) to play music specified by a file path and stop_music() to halt the music playback.
The core of the program resides in its main loop, which is an infinite while True: loop, enabling repeated user interactions. The user is presented with a menu displaying options: "play" to initiate music playback, "stop" to terminate music, and "quit" to exit the program.
User input is gathered via input(" "), allowing the program to capture the user's command. The program processes the input as follows: If "quit" is entered, the program exits the loop and terminates. If "play" is chosen, the user is prompted to provide the file path for the music, which is then played, with the program displaying the name of the file being played. If "stop" is selected, the program uses stop_music() to cease the music playback and informs the user accordingly. Any other input is met with an "Invalid input" response, signifying an unrecognized command.
The program continually presents the menu, enabling the user to perform these actions repeatedly during the program's execution, making it a flexible and interactive music player interface.
