<template>
    <section class="logo">
        <div class="google-logo">
            <img src="../assets/google-logo.png" alt="Google logo" class="google-image">
        </div>

        <div class="search-container">
            <form>
                <label class="search">
                    <img src="../assets/search.png" alt="search pic" class="search-pic">
                </label>
                <input type="text">
                <label class="microphone">
                        <img src="../assets/mic.png" alt="mic pic" class="mic-pic">
                </label>
            </form>
        </div>

        <div class="buttons">
            <button>Google Search</button>
            <button>I'm Feeling Lucky</button>
        </div>
        <div class="language-list">
            <p>Google offered in: </p>
            <a class="language">Română</a>
            <a class="language">Magyar</a>
            <a class="language">Deutsch</a>
        </div>
    </section>
</template>

<style>
.logo {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 63vh;
    cursor: pointer;
}

.google-logo {
    display: flex;
    justify-content: center;
}

.logo .search-container {
    margin-top: 25px;
}

.logo .search-container form {
    position: relative;
}

.logo .search-container form label.search {
    position: absolute;
    left: 17px;
    top: 13px;
}

.logo .search-container form label.microphone {
    position: absolute;
    right: 20px;
    top: 9px;
    cursor: pointer;
}

.logo .search-container form input {
    font-size: 16px;
    padding:  13px; 
    width: 300px;
    border: 1px solid #dadce0;
    border-radius: 30px;
    outline: none;
    padding-left: 50px;
    padding-right: 50px;
}

.logo .search-container form input:hover {
    box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
}

.logo .buttons {
    margin-top: 30px;
}

.logo .buttons button {
    background-color:#F8F9FA;
    padding: 8px 15px;
    border-radius: 5px;
    border: 1px solid #F8F9FA;
    cursor: pointer;
    margin: 0 5px;
    font-size: 14px;
    font-family: sans-serif;
    color: #444647;
}

.logo .buttons button:hover {
    cursor:pointer;
    border: 1px solid #dadce0;
    box-shadow: 0px 1px 1px rgba(0,0,0,0.15);
}

.logo .language-list {
    padding-top: 30px;;
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin: 5px10px;
    font-size: 13px;
    font-family: arial,sans-serif;
    align-items: flex-start;
}

.logo .language-list .language {
    display: flex;
    align-content: space-around;
    margin: 0px 5px;
    color: #0300a8;
    text-decoration: underline;
}

.search-pic {
    height: 20px;
    width: 20px;
}
</style>