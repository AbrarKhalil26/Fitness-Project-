# 🏋️ Fitness Project  
A modern fitness web application that allows users to discover exercises, view detailed workout instructions, and explore related videos for better training guidance.  


### 📌 Project Description  
This application enables users to:  
- Search for exercises by name, body part, target muscle, or equipment.  
- Browse different categories of exercises with a horizontal scroll UI.  
- View detailed information about each exercise (name, target muscle, equipment, etc.).  
- Watch related YouTube workout videos directly in the app.  
- Explore similar exercises by target muscle or equipment.  
- Enjoy a responsive, clean, and modern Material UI design.  


### 🚀 Features  
✔️ Search functionality with filtering (body part, equipment, etc.)  
✔️ Exercise detail pages with instructions  
✔️ YouTube video integration for workouts  
✔️ Similar exercises recommendations  
✔️ Horizontal scroll for exercise categories  
✔️ Responsive UI with Material UI  
✔️ Loading states and error handling  


### 🛠 Tech Stack  
- React 18 – Frontend library  
- React Router DOM – Navigation between pages  
- Material UI (MUI) – Styling and components  
- @emotion/react & @emotion/styled – CSS-in-JS styling  
- React Horizontal Scrolling Menu – Horizontal scroll UI  
- React Loader Spinner – Loading states  
- ExerciseDB API – Exercise data (name, body part, target, equipment)  
- YouTube Search API – Fetch workout videos  


### 📡 API Endpoints Overview  
- **ExerciseDB API** 👉 [Link](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel)  
  - Get all exercises  
  - Get exercise by ID  
  - Get exercises by body part  
  - Get exercises by target muscle  
  - Get exercises by equipment  

- **YouTube Search API** 👉 [Link](https://rapidapi.com/h0p3rwe/api/youtube-search-and-download?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel)  
  - Get related workout videos by exercise name  


### ⚙️ How to Run Locally  
1. Clone the repository  
2. Run `npm install`  
3. Add your **RapidAPI keys** for ExerciseDB & YouTube Search in `fetchData.js`  
4. Run `npm start`  
5. Open in browser at `http://localhost:3000`  

### 🎨 Design Preview
![Fitness App](https://github.com/AbrarKhalil26/YouTube-Project/raw/main/public/design/design.png)
