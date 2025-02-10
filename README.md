# 📧 Email Application  

## 🔹 Overview  
This application automates email account creation for new hires. It generates emails, assigns departments, creates secure passwords, and allows users to manage their email settings easily.  

## 🚀 Features  
- ✅ **Email Generation** → `firstname.lastname@department.company.com`  
- ✅ **Department Assignment** → Sales, Development, Accounting (optional)  
- ✅ **Random Password Generation** for security  
- ✅ **Manage Settings** → Change password, set mailbox capacity, add alternate email  
- ✅ **View User Info** → Name, email, and mailbox capacity  

## 💻 Quick Example  
```java
Email email = new Email("John", "Doe");
email.setMailboxCapacity(500);
email.setAlternateEmail("johndoe.personal@gmail.com");
System.out.println(email.showInfo());

🎯 Why Use It?
✔️ Saves time
✔️ Ensures consistency
✔️ Enhances security

Simple, fast, and efficient! 🚀
