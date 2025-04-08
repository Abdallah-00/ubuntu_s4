1. List **all running processes** and save the output to `~/processes.txt`.
  ![image](https://github.com/user-attachments/assets/e96c9386-0d3c-4579-a76e-0adb3d04ac19)

2. Find the **PID (Process ID)** of the `sshd` service.
  ![image](https://github.com/user-attachments/assets/91ec2cdb-4098-47a9-adfc-8e8989532a0c)

3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds.

4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser.
  ![image](https://github.com/user-attachments/assets/38324ffc-0782-4409-be2e-50143ed8067e)

5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.
  ![image](https://github.com/user-attachments/assets/f17eeb1a-32a6-4705-b1ea-680c5ad89a51)

6. **Restart the `cron` service** and verify its status.  
  ![image](https://github.com/user-attachments/assets/86c0a07c-74da-4aff-8d25-40d2824c6aaa)

7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.
  ![image](https://github.com/user-attachments/assets/f28b0701-5d82-470f-adcb-13fc6d7c9c56)

8. **Extract** the tarball into `~/logs_backup/`.
  ![image](https://github.com/user-attachments/assets/757cc6cc-d40b-49f1-bb83-4cc9a9cdc4a0)

9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.
  ![image](https://github.com/user-attachments/assets/23580898-3f82-4de2-bdf3-e8e5fcd41449)

10. Compress `~/processes.txt` using `gzip`.
  ![image](https://github.com/user-attachments/assets/ec6fde36-03a3-499a-aa38-c6b1ac3b180f)

11. **Decompress** it and compare file sizes using `ls -lh`.

13. **Install `htop`** (a process viewer) using your package manager.
    ![image](https://github.com/user-attachments/assets/18cc3533-dde1-47eb-9518-e84e7f7e122b)
  
14. **Search for the package `nginx`** (or `httpd`) but do not install it.  
    ![image](https://github.com/user-attachments/assets/6890a601-8abb-4224-8b4f-584b10ccdc7c)
    ![image](https://github.com/user-attachments/assets/03ccfb48-0fbc-47ca-973d-bdfd9a5df60a)


15. **Remove the `vim` editor** (if installed) and then reinstall it.  
    ![image](https://github.com/user-attachments/assets/bb38a098-e4a3-425b-8f46-9e44c026a62d)


16. Use `wget` to download the Linux kernel source:  
    ![image](https://github.com/user-attachments/assets/77308043-7ec5-40f1-be8c-93c5d5606f3f)

    ```  
17. Use `curl` to fetch **Google’s homepage** and save it as `google.html`.
    ![image](https://github.com/user-attachments/assets/ba1501ef-d400-4b65-a22e-71506acab589)


18. **Create a new VM** (e.g., VirtualBox/Cloud instance), add a user to the `sudoers` group, and run `apt update && apt upgrade`. 
19. **Generate an SSH key pair** using `ssh-keygen`.
    ![image](https://github.com/user-attachments/assets/7e3c984d-09bb-43d8-b5c2-df3f4460038f)

20. **Copy your public key** to the remote server:  
21. **SSH into the server** and verify with `hostname`.  
22. **Transfer the archived file** (e.g., `archive.tar.gz`) to the remote server using ssh copy way (don’t copy/paste >>> you have to search)
