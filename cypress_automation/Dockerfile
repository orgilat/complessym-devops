FROM cypress/included:12.17.1

# צור תקיית עבודה
WORKDIR /app

# העתק את כל קבצי הפרויקט פנימה
COPY . .

# התקנת תלויות
RUN npm install

# הפקודה שתורץ כשמריצים את הקונטיינר
CMD ["npx", "cypress", "run"]
