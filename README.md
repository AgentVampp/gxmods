body, html {
    margin: 0;
    padding: 0;
    overflow: hidden;
    height: 100%;
    background-color: #e0f7fa; /* Background color */
}

.background {
    position: relative;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.bunny {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: auto; /* Maintain aspect ratio */
    height: 100%; /* Cover full height */
    object-fit: cover; /* Cover the whole area */
    z-index: -1; /* Send it to the background */
}
