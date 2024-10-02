# CitySphere
header {
    background-color: rgba(44, 62, 80, 0.8); /* Dark blue-grey with transparency */
    color: #ecf0f1; /* Light grey */
    padding: 1rem;
    display: flex;
    justify-content: center; /* Center all elements horizontally */
    align-items: center;
    position: relative;
}

header h1 {
    color: #ecf0f1; /* Light grey for the heading */
    font-size: 3rem; /* Larger font size */
    font-family: 'Playfair Display', serif; /* New font style */
    text-align: center;
    margin: 0; /* Remove extra margin */
    flex-grow: 1; /* Ensure h1 takes up available space */
}

nav {
    position: absolute; /* Make navigation links float */
    right: 20px; /* Align navigation links to the right */
    top: 50%;
    transform: translateY(-50%); /* Vertically center nav */
    display: flex;
    gap: 1rem;
}
