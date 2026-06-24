
Topic: Combining Symbolic and Numeric Permissions
What I Learned
* Numeric permissions use numbers such as 600, 640, 700 and 755.
* Symbolic permissions use letters such as u, g, and o.
* Permissions can be modified using either numeric or symbolic methods.
* I can read permission output from ls -l and understand what each permission means.

Commands Used
chmod 600 private-diary.txt
chmod 700 journal.txt
chmod 755 backup.sh
chmod 644 goals.txt

chmod o-r goals.txt
chmod u+x backup.sh
chmod o-rwx private-diary.txt

ls -l

Practice Project
* Created a Personal Organization Lab.
* Protected a private diary using 600 permissions.
* Created a journal file using 700 permissions.
* Created an executable backup script using 755 permissions.
* Modified file permissions using symbolic mode.
Challenges
* Understanding how permission numbers are calculated.
* Remembering the difference between symbolic and numeric permissions.
* Reading and interpreting ls -l output.
Result
* I can now use both numeric and symbolic permissions and understand how Linux controls access to files.
