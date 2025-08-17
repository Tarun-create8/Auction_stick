# 🏆 Real-Time Auction Monitoring System  

A smart, sensor-based auction system that makes bidding faster, more accurate, and fully transparent.  
Instead of auctioneers struggling to notice raised paddles, bidders get **motion-sensing sticks**.  
When raised, the stick automatically sends the bid to a central receiver – no delays, no human errors.  

It’s like an **IPL-style auction**, but smarter. ⚡  

---

## ✨ Features  
- 🎯 **Real-time bid detection** using MPU6050 motion sensors.  
- 📡 **Low-latency wireless communication** with ESP-NOW (no internet needed).  
- 💡 **LED indicators** show which bidder placed a bid instantly.  
- 📊 **Excel logging** – every player, bidder, amount, and sold/unsold status is stored automatically.  
- 🛠 **Scalable & cost-effective** – built with affordable components (ESP32 + MPU6050).  
- 🏟 Works for sports auctions, charity events, property bidding, and more.  

---

## 🔧 Tech Stack  
- **Hardware**: ESP32, MPU6050, LEDs  
- **Software**: Arduino IDE (C++), Excel data logging (via Python/Arduino integration)  
- **Protocol**: ESP-NOW (fast peer-to-peer communication)  

---

## 📸 Demo  

### Hardware Setup  
![setup](docs/setup.jpg)  

### Auction in Action  
- LED lights up when a bid is placed  
- Live results on Serial Monitor  
- Excel sheet stores the auction history  

---

## 👨‍💻 My Contribution  
I worked on:  
- ✍️ Adding the **Excel data storage feature** to log auction results.  
- ⚙️ Calibrating sensors & fine-tuning tilt detection (so accidental movements don’t trigger bids).  
- 🔄 Implementing reliable ESP-NOW communication between bidder sticks & receiver.  
- 🧪 Testing with mock auctions, fixing bugs, and making the system more practical for real use.  

In short → I made sure the system is not just a demo, but a **usable solution**.  

---

## 🚀 How to Run  

1. Install **Arduino IDE** and add ESP32 board support.  
2. Connect ESP32 boards via USB and upload the sender/receiver code.  
3. Power up the MPU6050 + ESP32 sticks.  
4. Run the **receiver ESP32** and check bids via LEDs & Serial Monitor.  
5. Auction data is saved automatically into an **Excel sheet** for records.  

---

## 🌟 Future Improvements  
- 📱 Mobile app integration for real-time auction dashboards.  
- ☁️ Cloud storage (Firebase/Google Sheets) for online access.  
- 🎤 Voice announcements of bids and results.  
- 🔔 Buzzer alerts for final call before "sold".  

---

## 📜 License  
This project is for **educational purposes**.  
Feel free to fork and improve it! 🚀  

