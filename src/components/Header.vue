<template>
    <header class="header">
        <ul>
            <li>
                <a href="https:mail.google.com">Gmail</a>    
            </li>
            <li>
                <a href="https://images.google.com/">Images</a>    
            </li>

            <li>
                <div class="dropdown-apps">
                    <img src="../assets/google-apps.png" alt="google apps" class="appimg">
                </div>
            </li>
            <li>
                <img src="../assets/account-image.png" alt="account image" class="accimg">
            </li>
        </ul>
    </header>
</template>
<script>
</script>

<style>
.dropdown-apps:hover .dropdown-content-apps {
    display: block;
}

.appimg { 
    max-height: 32px;
}

.appimg:hover {
    background-color: #dadce0;
    border-radius: 50%;
} 

.accimg {
    width: 32px;
    height: 32px;
}

.accimg:hover {
    background-color: #dadce0;
    border-radius: 50%
}

.header {
    display: flex;
    justify-content: flex-end;
    padding: 12px 0;
}

.header ul {
    display: flex;
    align-items:center;
}

.header ul img {
    border-radius: 50%;
}

.header ul li {
    margin: 0 12px;
    display: flex;
    align-items:center;
    justify-content: space-evenly;
}
</style>