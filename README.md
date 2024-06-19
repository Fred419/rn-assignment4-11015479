# rn-assignment4-11015479
This is a React Native application that allows users to search for job listings. The app includes a login screen where users can enter their name and email, and a home screen that displays popular and featured 
job cards.

## Components

### `login`
The `login` component displays a form where users can enter their name and email. Upon pressing the login button, the user's name and email are passed to the `home` component.

### `home`
The `home` component displays the user's email and name, as well as two sections for popular and featured job cards. The job cards are rendered using the `popularJobs` and `featuredJobs` components.

### `popularJobs` and `FeaturedJobs`
The `popularJobs` and `FeaturedJobs` are reusable components that display job information such as the job title, company, location, and salary. It accepts props for card details and styles the card as shown in the provided UI mockup.

## Setup

1. Clone the repository: `git clone https://github.com/Steve2a/rn-assignment4-11297632.git`
2. Install dependencies: `npm install`
3. Start the development server: `npm start`

## Dependencies

- `react-navigation`: For navigation between screens
- `styled-components`: For styling React Native components

## Screenshots
![WhatsApp Image 2024-06-19 at 18 53 56_17aee64c](https://github.com/Fred419/rn-assignment4-11015479/assets/170224850/e1abcb8a-750d-4141-b76f-867dc7bbde5c)
![WhatsApp Image 2024-06-19 at 18 53 49_6daf0751](https://github.com/Fred419/rn-assignment4-11015479/assets/170224850/dbdf2128-b801-4d1e-8f74-905d48da655d)
![WhatsApp Image 2024-06-19 at 18 53 53_b9453ce1](https://github.com/Fred419/rn-assignment4-11015479/assets/170224850/28b050b7-21c5-41cf-93b5-5e5f371a2ba8)
![WhatsApp Image 2024-06-19 at 18 53 46_16bfda73](https://github.com/Fred419/rn-assignment4-11015479/assets/170224850/0f39b300-c923-4a2b-a384-91886852db12)



