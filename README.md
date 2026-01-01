# Smart-Logging
Designed to be easier to use and better in some ways compared to python's inbuilt logging module.
# Features
 Easy formatting
 Custom stdout handles
 Supports multiple file logging

# How to use
SmartLogging is a minimal, flexible logging system for Python that lets you quickly write messages to the console, files, or both, with fully customizable formatting and optional component tags. To start, create an instance of the output class, optionally specifying a file path with stdout and enabling auto_open to immediately open the file for writing. Use the set_handles method to define where the log messages should go — "console_out" for the terminal, "file_out" for a file, or both. You can customize the format of your messages using set_setting, replacing placeholders ^time^, ^level^, ^component^, and ^message^ to suit your style. SmartLogging supports three main logging levels: print_info, print_warn, and print_error, each of which can include an optional component parameter to identify the source of the message. You can clear the log file with clear and safely close it with close_stdout. Multiple independent loggers can coexist, each with separate files, formats, and handles, allowing you to log different subsystems simultaneously without interference. SmartLogging is lightweight, intuitive, and designed to make logging easy and human-readable, making it ideal for scripts, small apps, or even game development where simplicity and flexibility matter most.
|brought to you by chatgpt|
