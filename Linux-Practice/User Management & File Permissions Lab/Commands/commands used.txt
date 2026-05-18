Commands Used:

- Create User
  sudo su
  adduser sampleuser
  sudo
  adduser guestuser
  ls

- Create Group
  sudo groupadd team_test

- Add User to Group
  sudo usermod -aG team_test sampleuser
  sudo usermod -aG team_test guestuser

- Change Permissions
  touch file_permission.txt (new file)
  touch file_permission2.txt (new file)
  chmod 764 file_permission.txt
  chmod 777 file_permission2.txt
