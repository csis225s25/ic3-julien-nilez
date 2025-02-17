# In Class Problem Set 3
# Julien Niles, Ben Antoniuk


I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
Old line 43: cBox1 = new JComboBox(s1);

New line 43: cBox1 = new JComboBox<String>(s1);

**What caused it to stop working?**
It didn't work properly because we did not specify what type of variable would be stored in the input value.
