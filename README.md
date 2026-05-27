# 🐹 鼠鼠的干饭抉择器！
<img width="118" height="125" alt="Screenshot 2026-05-26 at 8 32 41 PM" src="https://github.com/user-attachments/assets/0b2436db-d51f-4dd5-b37d-d9c9caa11fd2" />

A cute little food decision helper for people who are hungry, tired, and absolutely not in the mood to answer the eternal question

What should I eat today?

This project is a lightweight web app that helps users find nearby food options based on distance, cuisine, budget, open now preference, and decision mode. It uses browser location and public map data to suggest real nearby places, then sends users to Google Maps for navigation.

No account.  
No login.  
No Google API key.  
Just click the pudding button and let the hamster do the thinking.

## ✨ What it does

This tool helps users narrow down food choices when they are too hungry to think.

Users can choose

1. Walking distance
2. Cuisine type
3. Budget level
4. Open now preference
5. Decision mode

Then the app returns a small list of nearby food options with distance estimates and Google Maps navigation links.

The goal is not to build another serious restaurant app.  
The goal is to make deciding what to eat feel lighter, softer, and a little more fun.

## 🐾 Why I made this

Choosing food sounds simple, but somehow it becomes a daily crisis.

I wanted to build something small and useful that feels warm instead of stressful. The design is soft, playful, and a little silly on purpose. The hamster does not judge your cravings. It simply tries its best.

This project was also a way for me to practice building a real interactive web tool using HTML, CSS, and JavaScript.

## 🧁 Main features

### Nearby food search

The app uses browser geolocation to find restaurants near the user.

### Preference filters

Users can filter by distance, cuisine, budget, and current open status.

### Decision modes

The app supports different moods

1. Closest
2. Best rated style sorting based on available public data
3. Random
4. Surprise me

### Google Maps navigation

Each result includes a button that opens Google Maps, so users can quickly check the route, hours, and final details.

### Cute interaction design

The app uses a pudding button, soft cards, animated food icons, and little hamster messages to make the experience feel more friendly.

## 🛠️ Tech stack

HTML  
CSS  
JavaScript  
Browser Geolocation API  
OpenStreetMap public data  
Overpass API  
Google Maps links for navigation

## 🌍 About the data

This project does not use a paid Google Places API key.

Nearby restaurant data comes from public OpenStreetMap data through Overpass API. This means the app can show real nearby places without requiring users to create an account or pay for an API.

Because the data is public and community maintained, some information may be incomplete. Opening hours, ratings, and restaurant details should still be checked in Google Maps before going.

## 🚀 How to run locally

1. Download or clone this project

2. Open the folder in VS Code

3. Install the Live Server extension if you have not installed it yet

4. Right click `index.html`

5. Choose `Open with Live Server`

6. Allow location access in the browser

7. Click the pudding button

That is it. The hamster is ready.

## 📍 Location permission

The app needs location permission to search nearby restaurants.

If location is blocked, the app cannot accurately find restaurants around the user. In that case, refresh the page and allow location access again.

## 🍜 Current limitations

This is a small front end project, not a full production restaurant platform.

Current limitations include

1. Restaurant data may be incomplete
2. Ratings are not always available
3. Open now status depends on available public data
4. Some places may not have full address information
5. Google Maps should still be used to confirm route and business hours

## 🌱 Future ideas

Things I would love to add later

1. Save favorite restaurants
2. Add a manual location input
3. Add food mood options like cozy, spicy, healthy, quick, or treat myself
4. Show a small map preview
5. Add better fallback results when public map data is slow
6. Make the hamster react differently based on the result

## 💛 Final note

This project is for everyone who has ever opened three food apps, scrolled for twenty minutes, and still had no idea what to eat.

Let the hamster pick.

You deserve a good meal.
