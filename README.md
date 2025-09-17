# Automated Attendance System for Rural Schools

### 📌 Project Overview
An offline, lightweight **QR-based Attendance System** designed for rural schools. Teachers scan student QR codes within a set timer (e.g., 15 mins); absentees are auto-marked. Data is stored locally, exported as CSV, and visualized with charts. Built with HTML, CSS, JS—optimized for low-end devices.

### 🚀 Features
- 📷 **QR Code Attendance** – Unique QR per student  
- ⏳ **Custom Timer** – Auto-absent after expiry  
- 📊 **Charts & Logs** – CSV export + attendance trends  
- 📱 **Offline Friendly** – Works on low-end devices, minimal memory  
- 💾 **Local Storage** – JSON + CSV export support  

### 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Libraries:** jsQR, Chart.js  
- **Data Storage:** JSON, CSV
  
### 📝 Future Improvements
- Cloud/Backend integration  
- Mobile App (Android/iOS)  
- Google Sheets/Excel API sync  


you can run it on the laptop and try some id's like this one... 

const studentDatabase = {
            '9': {
                'A': [
                    { id: "9A001", name: "Ramesh Kumar" },
                    
                    { id: "9A002", name: "Sita Devi" },
                    
                    { id: "9A003", name: "Amit Sharma" },
                    
                    { id: "9A004", name: "Priya Singh" },
                    
                    { id: "9A005", name: "Vikash Yadav" }
                ],

                
                'B': [
                    { id: "9B001", name: "Sunita Kumari" },
                    
                    { id: "9B002", name: "Anil Verma" },
                    
                    { id: "9B003", name: "Sonal Patel" },
                    
                    { id: "9B004", name: "Raghav UB" },
                    
                    { id: "9B005", name: "Meera Jain" }
                ],

                
                'C': [
                    { id: "9C001", name: "Rohit Gupta" },
                    
                    { id: "9C002", name: "Kavya Reddy" },
                    
                    { id: "9C003", name: "Arjun Singh" },
                    
                    { id: "9C004", name: "Pooja Sharma" },
                    
                    { id: "9C005", name: "Deepak Kumar" }
                ]
            },

            
            '10': {
                'A': [
                    { id: "10A001", name: "Rajesh Patel" },
                    
                    { id: "10A002", name: "Sneha Agarwal" },
                    
                    { id: "10A003", name: "Manoj Kumar" },
                    
                    { id: "10A004", name: "Ritu Singh" },
                    
                    { id: "10A005", name: "Suresh Yadav" }
                ],

                
                'B': [
                    { id: "10B001", name: "Anjali Sharma" },
                    
                    { id: "10B002", name: "Karan Verma" },
                    
                    { id: "10B003", name: "Nisha Gupta" },
                    
                    { id: "10B004", name: "Rahul Jain" },
                    
                    { id: "10B005", name: "Divya Reddy" }
                ],

                
                'C': [
                    { id: "10C001", name: "Ashok Singh" },
                    
                    { id: "10C002", name: "Geeta Kumari" },
                    
                    { id: "10C003", name: "Vinod Sharma" },
                    
                    { id: "10C004", name: "Sunita Patel" },
                    
                    { id: "10C005", name: "Mukesh Kumar" }
                    
                ]
