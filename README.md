# 🚀 AWS Scalable Infrastructure with Monitoring and Alerts

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)

A robust, production-ready AWS infrastructure implementing auto-scaling across multiple availability zones with enhanced security and monitoring capabilities.

## 🎯 Features

- **High Availability**: Deployment across multiple AWS Availability Zones
- **Auto Scaling**: Automatic scaling based on demand metrics
- **Load Balancing**: Application Load Balancer for traffic distribution
- **Security**: VPC with public/private subnets and security groups
- **Monitoring**: Integrated event monitoring and notification system
- **IAM Integration**: Secure access management with AWS IAM

## 🏗️ Architecture

![Architecture Diagram](./assets/architecture.png)

### Architecture Components

- **VPC Configuration**: Multi-AZ setup with public and private subnets
- **Load Balancer**: Application Load Balancer for traffic distribution
- **Auto Scaling**: EC2 auto-scaling groups for dynamic capacity
- **Security Groups**: Configured for maximum security
- **Internet Gateway**: Managed internet access
- **Event System**: Automated monitoring and notification


## 📸 Deployment Screenshots

<div class="screenshot-gallery">
    <!-- Example Screenshot -->
    <div class="screenshot-box">
        <img src="./assets/dashboard-screenshot.png" alt="AWS Auto Scaling Dashboard" class="screenshot">
       

<div class="screenshot-box">
        <img src="./assets/metrics-screenshot.png" alt="Example Deployment Screenshot" class="screenshot">
    </div>
</div>

## 🚀 Deployment Guide

### Prerequisites

- AWS CLI installed and configured
- IAM user with appropriate permissions
- Git installed on your local machine

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/aws-autoscaling-app.git
cd aws-autoscaling-app
```

2. Configure AWS credentials:
```bash
aws configure
```

3. Deploy the infrastructure:
```bash
# Install required packages on EC2 instances
amazon-linux-extras install epel -y
yum install stress -y

# Test auto-scaling trigger (optional)
stress --cpu 1 --timeout 800 &
```

## 🔍 Monitoring

The application includes comprehensive monitoring through:
- CloudWatch Metrics
- Auto Scaling Events
- Load Balancer Logs
- Custom Event Notifications

## 🛡️ Security

- VPC isolation
- Security group rules
- IAM role-based access
- SSL/TLS encryption
- Regular security audits

## 📊 Performance

The architecture is designed to handle:
- High-traffic loads
- Sudden traffic spikes
- Seamless scaling
- Zero-downtime deployments

## 👤 Developer

<div align="center">
  <img src="./assets/profile.jpg" width="200px" style="border-radius: 50%; margin-bottom: 20px;">
  <h3>Debjyoti Shit</h3>

</div>


## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🤝 Contributing

Contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## 📞 Contact

- GitHub: [Debjyoti2004](https://github.com/Debjyoti2004)
- LinkedIn: [Debjyoti Shit](www.linkedin.com/in/debjyotishit)
- Email: debjyotishit27@gmail.com

## ⭐ Support

If you found this project helpful, please consider giving it a star! It helps others discover the project.

---
<div align="center">
Made with ❤️ by Debjyoti Shit
</div>