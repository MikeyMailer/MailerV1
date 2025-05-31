# Mikey -NodeSender - Advanced Email Sending

## 🚀 Overview
NodeSender is a sophisticated, enterprise-grade email sending system built with Node.js that provides comprehensive email marketing capabilities with advanced content processing, intelligent SMTP management, and powerful automation features.

## ✨ Core Features

### 📧 **Email Campaign Management**
- Bulk Email Sending
- Campaign Statistics
- Progress Monitoring
- Recipient Management
- Email Validation

### 🔄 **Rotation Systems**

#### **SMTP Server Rotation**
- Multiple SMTP Support
- Sequential/Random/Weighted Strategies
- Health Monitoring
- Load Balancing
- Priority System

#### **Content Rotation**
- Template Rotation
- Subject Line Rotation
- Sender Name Rotation
- From Email Rotation

### 🎯 **Dynamic Content Processing**

#### **MACRO System**
- Custom MACRO Files
- Sequential Processing
- Random Selection
- Automatic Management

#### **Mail Merge**
- Recipient Variables
- Dynamic Data
- Business Context
- Geographic Data
- Marketing Variables

#### **Spintax Support**
- Content Variation
- Nested Spintax
- Automatic Processing

### 🔐 **Header Management**

#### **Smart SMTP Detection**
- Provider Recognition
- Provider-Specific Headers
- Authentication Headers

#### **Header Customization**
- Header Rotation
- Template Variables
- Randomization

### 🌐 **Network Features**
- Proxy Support (SOCKS5/HTTP)
- Proxy Rotation
- Connection Pooling
- Timeout Handling

### 📊 **Content Optimization**
- Spam Trigger Detection
- Content Optimization
- HTML Processing
- Image Handling
- Attachment Support

### ⚙️ **Configuration**
- Concurrency Management
- Delay Configuration
- Retry Logic
- Rate Limiting

### 🔍 **Debug & Monitoring**
- Comprehensive Debug Mode
- Visual Debug Display
- Real-time Statistics
- Error Tracking

### 🔒 **Security & Compliance**
- License Protection
- Secure Connections
- Authentication
- Privacy Features

### 📁 **File Management**
- Template System
- Recipient Lists
- Cache Management
- Log Files

## 🛠️ **Technical Specifications**

### **Supported Protocols**
- SMTP with STARTTLS
- SMTP with SSL/TLS
- Authenticated SMTP
- Proxy Tunneling

### **Content Formats**
- HTML Emails
- Plain Text Fallback
- Multipart Messages
- PDF Attachments
- Image Attachments

### **Provider Compatibility**
- Gmail/Google Workspace
- Microsoft Outlook/Office 365
- Yahoo Mail
- Amazon SES
- SendGrid
- Mailgun
- Custom SMTP Servers

## 📈 **Performance Features**
- Connection Pooling
- Parallel Processing
- Memory Management
- Error Recovery

## 🎨 **User Experience**
- Beautiful Console Interface
- Real-time Feedback
- Detailed Debug Output
- Progress Indicators

## 🔧 **Command Line Interface**
```bash
# Send email campaign
node index.js send -r recipients.txt -c 5

Or Just Start sendEmail.bat
