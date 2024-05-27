# Linux-Necessary-Used-Commands

## Find IP and PORT

- [x] Find specific ip/port running or not on system using <b>grep</b> ☟
  ```sh
  ss -ltnp | grep 8001
  ```
  ```sh
  lsof -i -P -n | grep 127.0.0.1
  ```
- [x] Find all ip/port running on system ☟
  ```sh
  ss -ltnp
  ```
  ```sh
  lsof -i -P -n
  ```  
