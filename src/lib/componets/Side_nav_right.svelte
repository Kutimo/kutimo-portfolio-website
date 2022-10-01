     
<div class="side_nav">
<a href="mailto:test@test.com"><p>blblabla@mail.com</p></a>
<img src="/images/line.svg" alt="n/a">
</div>

<style>
    .side_nav {
    width: 10%;
    height: 100vh;
    right: 0px;
    left: auto;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    flex-direction: column;
    position: fixed;
    text-align: center;
    }
    p {
    transform: rotate(90deg);
    margin-bottom: 50%;
    
    }
    a{
    text-decoration: none;
    color: var(--dark_color);
    }
    p:hover {
    color: var(--light_color);
    transition-delay: 300ms;
    transition: all 1.5s ease-out;
    font-size: 2rem;
    text-decoration: underline;
    }
</style>