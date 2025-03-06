**# Ease Tool for Maya**

## Installation and Usage Guide

### **Installation Steps:**
1. **Download the Script**: Save the script file as `ease_tool.py`.
2. **Move to Scripts Folder**: Place the file in Maya’s scripts directory:
   - Windows: `C:\Users\YourUsername\Documents\maya\scripts\`
   - macOS: `/Users/YourUsername/Library/Preferences/Autodesk/maya/scripts/`
   - Linux: `/home/YourUsername/maya/scripts/`
3. **Restart Maya**: Restart Maya to ensure the script is recognized.

### **Adding to Shelf:**
1. Open **Script Editor** in Maya.
2. Switch to the **Python** tab.
3. Enter the following command:
   ```python
   import ease_tool
   ease_tool.initialize_plugin()
   ```
4. Highlight the code and **drag it to the Shelf**.
5. Assign an icon for quick access.

### **How to Use:**
1. Open the Graph Editor and select keyframes.
2. Set the **Ease Factor** (1-10).
3. Click **Apply Ease In** or **Apply Ease Out**.
4. To see instructions, click the **Instructions** button.

---

**# ابزار Ease برای مایا**

## راهنمای نصب و استفاده

### **مراحل نصب:**
1. **دانلود اسکریپت**: فایل را با نام `ease_tool.py` ذخیره کنید.
2. **انتقال به پوشه‌ی اسکریپت‌ها**: فایل را در مسیر اسکریپت‌های مایا قرار دهید:
   - **ویندوز**: `C:\Users\YourUsername\Documents\maya\scripts\`
   - **مک**: `/Users/YourUsername/Library/Preferences/Autodesk/maya/scripts/`
   - **لینوکس**: `/home/YourUsername/maya/scripts/`
3. **ری‌استارت مایا**: مایا را مجدداً راه‌اندازی کنید تا اسکریپت شناسایی شود.

### **افزودن به Shelf:**
1. **اسکریپت ادیتور** را باز کنید.
2. به تب **Python** بروید.
3. کد زیر را وارد کنید:
   ```python
   import ease_tool
   ease_tool.initialize_plugin()
   ```
4. کد را **انتخاب کرده و به Shelf بکشید**.
5. یک آیکون برای دسترسی سریع اختصاص دهید.

### **نحوه استفاده:**
1. وارد **Graph Editor** شده و کی‌فریم‌ها را انتخاب کنید.
2. مقدار **Ease Factor** (بین 1 تا 10) را تنظیم کنید.
3. روی **Apply Ease In** یا **Apply Ease Out** کلیک کنید.
4. برای مشاهده راهنما، دکمه **Instructions** را بزنید.

