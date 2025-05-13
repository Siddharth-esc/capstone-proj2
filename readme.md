body {
	background: linear-gradient(-45deg, #112D4E, #DBE2EF, #112D4E, pink);
	background-size: 400% 400%;
	animation: gradient 25s ease infinite;
	height: 100vh;
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}

.title{
    font-size: 129px;
    font-family: "DM Serif Display", serif;
    font-weight: 400;
    font-style: normal;
    color: var(--primary-text);
    letter-spacing: 0.5rem;
}

.caption{
        font-family: "Atkinson Hyperlegible", sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 34px;
        color: var(--secondary-text); 
        letter-spacing: 0.25rem;
}

@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Atkinson+Hyperlegible&family=DM+Serif+Display&display=swap');

:root{
    /* --primary-text: #546975; */
    --primary-text: #86b7d3;
    --secondary-text: white;
    --primary-btn: rgba(255, 68, 0, 0.918);
    --secondary-btn: rgba(128, 128, 128, 0.89);

    --primary-bodycolor: rgba(128, 128, 128, 0.89);
    /* --backgroundcolor-main: rgba(245, 222, 179, 0.315); */
}