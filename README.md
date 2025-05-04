# 🌟 Quote of the Day - Flask App

This is a simple and beautiful **Flask web application** that shows a random motivational quote each time the page is loaded.

## 🚀 Features

- Python Flask backend
- Bootstrap-powered UI
- Random quote displayed on each visit
- Easily deployable on AWS EC2

---

## 📦 Requirements

- Python 3
- pip

Install Flask:

```bash
pip3 install -r requirements.txt
```

---

## 🛠️ How to Run Locally

```bash
python3 app.py
```

Visit: [http://localhost:5000](http://localhost:5000)

---

## ☁️ How to Deploy on AWS EC2

1. Launch a new EC2 instance (Amazon Linux 2, t2.micro)
2. SSH into the instance:

```bash
ssh -i your-key.pem ec2-user@<your-ec2-ip>
```

3. Install Python and Flask:

```bash
sudo yum update -y
sudo yum install python3 -y
pip3 install --user Flask
```

4. Upload project files to EC2 (via `scp` or Git)
5. Run the app:

```bash
nohup python3 app.py &
```

6. Open `http://<your-ec2-ip>:5000` in your browser

Make sure to allow inbound traffic on port 5000 in your EC2 security group.

---
