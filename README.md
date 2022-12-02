<h1 align="center"> Hey! I am Júlio. </h1>
<div> 
  <p> ➤  Information Systems Student. </p>
  <p> ➤  Systems Development Technician. </p>     
  <p> ➤  18y. </p>    
  <p> ➤  Nothing's impossible. </p>     
  <p> ➤  Stay Flinston </p>    
</div>
<h1>  My Github Stats </h1>
<p align="center"> <img src="https://github-readme-streak-stats.herokuapp.com?user=AsTunO&theme=github-dark&date_format=M%20j%5B%2C%20Y%5D" /> </p>
<p align="center"> <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AsTunO&theme=github_dark"/> </p>
<div align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AsTunO&theme=github_dark"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=AsTunO&theme=github_dark"/>
</div>
<p align="center"> 
  
</p>

```java
public class MyLife {

    public static void main(String[] args) {

        Life mylife = new Life();
        mylife.start();

        while (true) {
            
            while(mylife.success == false) {
                mylife.tryAgain();
            }

            mylife.victories += 1;

            if (mylife.victories >= SUCCESS_CONDITION) {
                System.out.println("You have won the game!");
                break;
            }
        }
    }
} 
