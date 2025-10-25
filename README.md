# تظلم كليات التمريض - Nursing Colleges Complaints System

A modern, responsive web application for managing and searching nursing college complaints and requests using national ID numbers.

## 🌟 Features

### 🔍 **Advanced Search System**
- **National ID Search**: Search by national ID with instant results
- **Duplicate Handling**: Smart accordion system for multiple requests with same ID
- **Real-time Feedback**: Loading animations and status indicators

### 📊 **Smart Data Display**
- **Opinion Status Detection**: Automatic color coding based on committee decisions
  - 🟢 **Green**: Approved requests (`الموافقة`)
  - 🔴 **Red**: Rejected requests (`عدم الموافقة`)
  - ⚪ **Gray**: Pending/Other status
- **Full Opinion Banners**: Complete committee opinions displayed prominently
- **Responsive Cards**: Mobile-first design with smooth animations

### 🎨 **Modern UI/UX**
- **Arabic RTL Support**: Proper right-to-left text direction
- **Tailwind CSS**: Modern, responsive styling
- **Smooth Animations**: Fade-in, slide, and hover effects
- **Professional Design**: Clean, government-appropriate interface

### 📱 **Accordion System**
- **Multiple Results**: When duplicate IDs exist, shows all requests in expandable cards
- **Approval Status Banner**: Highlights when at least one request is approved
- **Interactive Navigation**: Click to expand/collapse individual requests
- **Visual Hierarchy**: Clear organization of multiple requests

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/AMohamedRaafat/ncc.git
   cd ncc
   ```

2. **Open in browser**:
   - For development: Use a local server (Live Server, Python's http.server, etc.)
   - For production: Deploy to any web hosting service

3. **Access the application**:
   - Open `index.html` in your browser
   - The application will automatically load `data.json`

## 📁 Project Structure

```
ncc/
├── index.html          # Main application file
├── data.json           # Complaints data (31,732 records)
└── README.md           # This file
```

## 🔧 Technical Details

### **Frontend Technologies**
- **HTML5**: Semantic markup with RTL support
- **CSS3**: Custom animations and responsive design
- **JavaScript (ES6+)**: Modern async/await patterns
- **Tailwind CSS**: Utility-first CSS framework

### **Key Features Implementation**
- **Data Loading**: Asynchronous JSON data fetching
- **Search Algorithm**: Efficient filtering with duplicate detection
- **Animation System**: CSS keyframes with JavaScript triggers
- **Responsive Design**: Mobile-first approach with breakpoints

### **Browser Compatibility**
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📊 Data Structure

The application works with JSON data containing complaint records with the following structure:

```json
{
  "i": "1",
  "name": "اسم الموظف",
  "id": "الرقم القومي",
  "current": "الادارة الحالية",
  "requested": "الادارة المطلوبة",
  "attachments": "المرفقات",
  "opinion ": "رأي اللجنة",
  "committeeResolution": "قرار اللجنة"
}
```

## 🎯 Usage

### **Single Search**
1. Enter national ID in the search field
2. Click "بحث" or press Enter
3. View results in a detailed card format

### **Multiple Results**
1. When duplicate IDs exist, an accordion interface appears
2. Click on any request header to expand details
3. Approval status banner shows if any request is approved

### **Status Indicators**
- **Green Banner**: Approved requests
- **Red Banner**: Rejected requests  
- **Gray Banner**: Pending/Other status

## 🛠️ Development

### **Local Development**
```bash
# Start a local server
python -m http.server 8000
# or
npx live-server
```

### **Customization**
- **Colors**: Modify CSS variables in the `<style>` section
- **Animations**: Adjust timing in CSS keyframes
- **Data**: Replace `data.json` with your own dataset

## 📝 License

This project is developed for nursing colleges complaints management system.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For support and questions, please contact the development team.

---

**تطوير نظام تظلم كليات التمريض**  
*Nursing Colleges Complaints Management System*
