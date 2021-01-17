# Updated Portfolio

My updated portfolio provides information about me, showcases some of my most recent work, and links to my GitHub and LinkedIn profiles.

![alt-text](assets/updated-portfolio.gif)

## **Built With**
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [GitHub](https://github.com/)
* [Foundation](https://get.foundation/index.html)
*  Git - used to track changes to code
______________________________________________________________________________
  
### **Summary**

This updated portfolio was built using the Foundation CSS Framework. I've made use of modals as well as their styling options and used custom CSS. 

______________________________________________________________________________

#### **Code Snippet**

I encountered issues when using their built-in .button-hover-reveal-wrapper as it's not inherently responsive. I wanted to keep this feature so I decided to use Foundation's visibility classes to make two separate sections which appeared or disappeared based on screen size. On larger screens, one button reveals three underlying buttons while on the small screen the large button disappears and is replaced by three separate buttons. 

Large and Medium Screens:
```
            <div class="button-hover-reveal-wrapper hide-for-small-only">
                <label>Learn More</label>
                <a href="assets/Pamela_Gutierrez_-_Web_Developer (2).pdf" target="_blank"
                    class="button-hover-reveal">Resume</a>
                <a data-open="about_modal" class="button-hover-reveal">
                    About Me</a>
                <a data-open="projects_modal" class="button-hover-reveal">Projects</a>
            </div>
            <div class="icons hide-for-small-only" style="margin-top:100px;">
                <a href="https://github.com/pamela-gutierrez" target="_blank" class="button-hover-reveal"><i
                        class="fab fa-github fa-3x"></i></a>
                <a href="mailto:pgutierrez44@gmail.com" target="_blank" class="button-hover-reveal"><i
                        class="far fa-envelope fa-3x"></i></a>
                <a href="https://www.linkedin.com/in/pamela-gutierrez" target="_blank" class="button-hover-reveal">
                    <i class="fab fa-linkedin fa-3x"></i></a>
            </div>
```
On Small Screens - First of Three Buttons:
```
           <div class="grid-x show-for-small-only" style="margin-bottom:10px;">
                <div class="cell" style="margin-bottom: 70px;">
                    <div class="button-hover-reveal-wrapper show-for-small-only">
                        <label>Resume</label>
                        <!-- RESUME BUTTON -->
                        <a href="assets/Pamela_Gutierrez_-_Web_Developer (2).pdf" target="_blank"
                            class="button-hover-reveal">Resume</a>
                    </div>
                </div>
```


______________________________________________________________________________


#### **Deployed Link**

* [See Live Site](https://pamela-gutierrez.github.io/updated-portfolio/)

### **Author Links**

* **PAMELA GUTIERREZ**
* **UC Berkeley Coding Bootcamp**
  
- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/pamela-gutierrez) 
- [Link to LinkedIn](www.linkedin.com/in/pamela-gutierrez)



______________________________________________________________________________

#### **License**

This project is licensed under the MIT License