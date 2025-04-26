# 🎲 Lucky Game

เว็บเกมลอตเตอรี่ที่ให้คุณสามารถเชื่อมต่อกระเป๋า MetaMask เพื่อเข้าร่วมเล่นเกมเสี่ยงโชค และผู้ดูแลระบบสามารถเลือกผู้ชนะ หรือโอนสิทธิ์เจ้าของสัญญาได้

## 🔗 คุณสมบัติ

- เชื่อมต่อกระเป๋า MetaMask
- แสดงข้อมูลรางวัลรวม (Prize Pool)
- แสดงผู้เล่นที่เข้าร่วม (Players)
- แสดงผู้ชนะล่าสุด (Last Winners)
- ฟังก์ชันสำหรับเจ้าของสัญญา:
  - เลือกผู้ชนะ (Pick Winners)
  - โอนสิทธิ์เจ้าของสัญญา (Transfer Ownership)

## 🛠 วิธีการใช้งาน

### 1. ติดตั้ง MetaMask

หากยังไม่มี ให้ติดตั้ง MetaMask จาก [https://metamask.io/](https://metamask.io/)

### 2. เปิดไฟล์ HTML นี้ใน Browser

เช่น Chrome, Brave ที่รองรับ Web3

เปิดไฟล์ `index.html` หรือไฟล์ frontend ที่ให้ไว้ ผ่าน Browser

### 3. เชื่อมต่อกระเป๋า

- กดปุ่ม **"Connect MetaMask"**
- อนุญาตการเชื่อมต่อกระเป๋า

### 4. เข้าร่วมเกม

- กดปุ่ม **"Enter GAME"**
- จะมีการส่ง ETH จำนวนเล็กน้อย (ค่าเข้าเกม)

### 5. ฟังก์ชันเพิ่มเติมสำหรับเจ้าของสัญญา

หากคุณเป็นเจ้าของสัญญา จะมีปุ่ม:

- **"Pick Winners"** เพื่อเลือกผู้ชนะ
- **"Transfer Ownership"** เพื่อเปลี่ยนเจ้าของสัญญา

## 🧩 ข้อมูล Smart Contract

- **ที่อยู่สัญญา (Contract Address):**  
  `0xbaD9a176ae2bc379F3b9c91cf0F395B6e33ffd97`

- **Entry Fee:**  
  `0.00001 ETH`

- **ฟังก์ชันหลัก:**
  - `enterLottery()` - เข้าร่วมลอตเตอรี่ (payable)
  - `pickWinners()` - เลือกผู้ชนะ
  - `transferOwnership(newOwner)` - โอนเจ้าของสัญญา
  - `lotteryId()` - หมายเลขเกมปัจจุบัน
  - `prizePool()` - จำนวนเงินรางวัลรวม
  - `getPlayers()` - รายชื่อผู้เล่น
  - `getLastWinners()` - รายชื่อผู้ชนะก่อนหน้า

- **Event:**
  - `LotteryEntered`
  - `LotteryWinner`
  - `OwnershipTransferred`

## 📁 โครงสร้างไฟล์
randomgame1/ ├── 🖼 65061447.png ├── 📄 Aboutme.html ├── 📄 index.html ├── 🖼 JIWSPUNO.1.jpg ├── 📝 readme.md └── 🖼 wan.jpg
## ⚡ เทคโนโลยีที่ใช้

- HTML5 + CSS3
- JavaScript (Vanilla)
- Web3.js (ผ่าน CDN)
- MetaMask (Wallet Connection)

## 📝 หมายเหตุ

- ใช้งานบนเครือข่ายที่เหมาะสม เช่น Testnet (holeskytestnet)
- ตรวจสอบ Gas Fee ก่อนทำธุรกรรมทุกครั้ง