# 1. head

head – View the first lines of a file

         head <name of the file>

By default, it shows the first 10 lines.

📌 Show a specific number of lines:

         head -n 5 <file name>

          or 

          head -5 <file name>

  ![image](https://github.com/user-attachments/assets/3e435555-9e71-4b22-8ce2-4bd1b1e92d3b)

  example: head -5 input.txt

  ![image](https://github.com/user-attachments/assets/87429e06-acce-4f5d-8591-827925826f5a)


# 2. tail

  tail – View the last lines of a file

📄 Basic Usage:

      tail <file name>

By default, shows the last 10 lines.

📌 Show a specific number of lines:

      tail -n 12 <file name>

         or

      tail -12 <file name>

Example: tail -8 input.txt

![image](https://github.com/user-attachments/assets/eda15479-a76b-4ea7-a651-cb73141d05f6)


# Combination of both:

head -15 input.txt | tail -6

does the following:

head -15 input.txt outputs the first 15 lines from the file.

tail -6 then takes the last 6 lines from the output of the head command.

Given the 20-line city list in input.txt, the output would be:

![image](https://github.com/user-attachments/assets/eaff9cee-ab17-41d8-91ac-b02f346ace46)


# 3. more

View large files page by page

📄 Basic Usage:

         more <filename>
         
![image](https://github.com/user-attachments/assets/69beb801-97a4-4bb1-9278-3295df50dc0a)


# tail

The less command in Linux is a file pager that allows you to view (and optionally scroll through) large files one page at a time. It’s more powerful than more, as it lets you scroll both forward and backward within the file.

![image](https://github.com/user-attachments/assets/23b213e3-55c8-44a3-8563-e6fdfec81201)
