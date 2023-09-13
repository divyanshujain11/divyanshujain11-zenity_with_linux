![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/79dfb608-3b02-44a2-806a-c40bbfa8310e)


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

**2. Error Dialog Box:** 
Zenity allows users to display an error dialog box that displays an error message to the user. This can be useful when the user needs to be informed of an error in an application or script.

                        zenity --error

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/fed397bb-8604-4910-b5ee-1fa3e23b711c)

**3. Text Entry Dialog:-**
Zenity allows users to display a dialog box that prompts the user to enter a string of text. This can be useful in situations where the user needs to input a specific text for an application or script.

                        zenity --entry

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/cbb5edf0-fbd4-4d1c-acb3-865ebeb46cd1)

next click ‘OK’ , ‘hi all’ print in ternimal.

**4. File Selection Dialog:**
Zenity allows users to display a dialog box for selecting a file or directory from the file system. This can be useful when the user needs to specify a file or directory as input for an application or script.

                        zenity --file-selection

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/4499e7d0-6e42-489d-a998-ea3c569aa78e)

**5. Scale Dialog:**
Zenity allows users to display a scale dialog box, allowing the user to select a value within a range of predefined values. This can be useful in situations where the user needs to select a specific value for an application or script, such as setting the volume or brightness.

                        zenity --scale

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/7a9104a8-19b5-4028-a9b1-63bdceca1839)

**6. Question Dialog:**
- Zenity allows users to display a dialog box that prompts the user to answer a question with a yes or no response. This can be useful in situations where the user needs to confirm a choice or action for an application or script.

                        zenity --question

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/55295d91-2e40-4900-a2fa-29efe7ef5461)

**7. Color Selection Dialog:**
Zenity allows users to display a color selection dialog box, allowing the user to choose a color from a variety of options. This can be useful in situations where the user needs to select a specific color for an application or script.

                                zenity --color-selection

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/8a38f0b0-12d2-4f8f-af59-2b3904d6d6ee)

**8.Information Dialog ( — info):**
This dialog displays an informational message to the user.

                        zenity --info --text="This is an informational message."

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/8f70a32d-3041-4b8d-a1f3-030a81e7ea65)


**9. Warning Dialog ( — warning):**
Use this dialog to show a warning message to the user.

                        zenity --warning --text="Warning: Something went wrong"
![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/f31c93d1-9ebf-433d-941c-71d55092d173)



**10. List Dialog ( — list):**
Show a list dialog where the user can select items from a list. This example displays a list of fruits:

                        zenity --list --column="Selection" "Apple" "Banana" "Cherry" "Date"

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/03e766dc-554c-456c-987d-41ed0dda04fa)



**11. Progress Dialog ( — progress):**
Display a progress dialog with a progress bar.

                        for i in {1..100}; do echo $i; sleep 1; done | zenity --progress

![image](https://github.com/divyanshujain11/divyanshujain11-zenity_with_linux/assets/77712311/7b0618d5-9f76-42e2-a324-8a4e49e3063c)



