# Auction_stick
📌 Project Overview – Real-Time Auction Monitoring System

We built a smart auction system that makes bidding easier, faster, and more transparent. Instead of depending on auctioneers to spot raised hands or paddles, every bidder gets a stick with a motion sensor. When the stick is lifted, the system automatically detects the movement and sends the bid to a central receiver.

The auctioneer instantly sees a visual cue (LED lights) showing who placed the bid, while the system also logs the details into an Excel sheet. This means every bid, player, price, and sold/unsold status is recorded neatly for future reference.

It feels like an IPL-style auction, but smarter, automated, and error-free.

🔑 What it can do

Detects bids in real time using motion sensors.

Shows live feedback with LED indicators.

Simulates a real auction with players, base prices, bids, and results.

Stores all auction outcomes in an Excel sheet automatically.

Scales easily – more sticks (bidders) can be added without much effort.

Built with simple, affordable components (ESP32 + MPU6050).

👨‍💻 My Role in the Project

Here’s what I worked on:

Added the feature to save auction results into Excel, ensuring that no data is lost and the information can be used later for reports or analysis.

Helped in setting up the sensor calibration and fine-tuning the tilt angle, so normal hand movements don’t accidentally trigger a bid.

Worked on the software logic for communication between the bidder sticks and the main receiver using ESP-NOW.

Took part in mock auction tests, troubleshooting bugs, and making the system run smoothly without delays or packet losses.
