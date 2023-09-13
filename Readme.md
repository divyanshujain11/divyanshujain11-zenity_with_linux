**What is Zenity ?**


Zenity is a free and open-source graphical user interface (GUI) toolkit for Linux and Unix-like operating systems. It provides a simple and user-friendly way to create dialog boxes and windows in shell scripts and other scripting languages. Zenity is particularly useful for creating interactive dialogs in scripts that can be run from the command line or integrated into various automation and scripting tasks.

**Here are some key features and aspects of Zenity:**


**Dialog Types:** 

Zenity offers various types of dialog boxes, including message dialogs, file selection dialogs, text entry dialogs, list dialogs, progress bars, and more. These dialogs allow you to gather input from users or display information interactively.
**Scripting Language Support:**

Zenity can be used with a wide range of scripting languages, including Bash, Python, Perl, and more. It provides a command-line interface, making it easy to invoke from within scripts.
**Cross-Platform:**

While Zenity is primarily designed for Linux and Unix-like systems, there are efforts to make it available on other platforms. It may be possible to use Zenity on macOS and Windows with some additional configuration.
**Customization:** 

You can customize the appearance and behavior of Zenity dialogs to some extent, such as setting the window title, icons, and default values for input fields.
**Integration:** 

Zenity is often used to enhance the user experience in shell scripts. For example, you can use it to prompt users for input, display progress during lengthy operations, or present informative messages.
**Open Source:** 

Zenity is open source and is typically available in most Linux distributions’ package repositories. This means you can easily install it using package managers like APT, YUM, or Pacman.


Steps to Install Zenity in Linux

        yum install zenity

        zenity --version


![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/67089b93-7ff9-4a88-92ef-6ad3a8f5353b)

**Some of the basic Dialogs of Zenity can be invoked directly from the command line:**


**Quick Calendar Dialog:**

Zenity allows users to display a calendar dialog box, allowing the user to select a date from a calendar. This can be useful when the user needs to input a specific date for an application or script.

                        zenity --calendar


 ![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/3c309dc0-ce9b-4c9a-8e68-ddaaf84b8490)



