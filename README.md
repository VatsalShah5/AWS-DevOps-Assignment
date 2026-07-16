# AWS DevOps Engineer Intern Assignment

## Objective

Deploy a simple website on an AWS EC2 instance using Ubuntu and Nginx.

---

## AWS Services Used

- Amazon EC2
- Security Groups

---

## EC2 Configuration

- Operating System: Ubuntu
- Instance Type: t2.micro
- Security Group Rules:
  - SSH (Port 22)
  - HTTP (Port 80)

---

## Linux Commands Used

Update packages

```bash
sudo apt update
```

Install Nginx

```bash
sudo apt install nginx -y
```

Check Nginx status

```bash
sudo systemctl status nginx
```

Restart Nginx

```bash
sudo systemctl restart nginx
```

Check disk usage

```bash
df -h
```

Check memory usage

```bash
free -h
```

Check running processes

```bash
ps aux
```

---

## Website Deployment

- Created a custom `index.html` page.
- Replaced the default Nginx web page.
- Hosted the website on an AWS EC2 instance.
- Verified website accessibility using the EC2 Public IP.

---

## Project Files

- index.html
- README.md

---

## Author

**Name:** Vatsal Shah

**Email:** vatsalshah7852@gmail.com