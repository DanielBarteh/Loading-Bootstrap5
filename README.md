<p style="text-align: center;margin-bottom: -50px">
    <a href="https://dabram.ir/" target="_blank"><img src="https://dabram.ir/file/image/Dabram.png" width="400" alt="Dabram Logo"></a>
</p>

<p style=";justify-content: space-around;display: flex;align-content: center;justify-items: center">
<a href="https://dabram.ir" style="margin-right: 10px;margin-left: 10px;color: white;text-shadow: 0 0 20px white">Home</a>
<a href="https://dabram.ir/product" style="margin-right: 10px;margin-left: 10px;color: orangered;text-shadow: 0 0 20px white">product</a>
<a href="https://dabram.ir/workSamples" style="margin-right: 10px;margin-left: 10px;color: white;text-shadow: 0 0 20px white">WorkSamples</a>
<a href="https://dabram.ir/policy" style="margin-right: 10px;margin-left: 10px;color: orangered;text-shadow: 0 0 20px white">Policy</a>
</p>
<hr style="width: 50%;margin: 10px auto">


**Version 2.0.0.0 is Available :**
* Dark Mode + Light Mode

<p style="text-align: center">
    <a href=""><img src="images/DarkMode.png" width="400" alt="Dark Mode"></a>
    <a href=""><img src="images/LightMode.png" width="400" alt="Light Mode"></a>
</p>



## About This Project (Loading-Bootstrap5)
* This project made with Boostrap5 and Jquery.
* Bootstrap5 is in node_modules folders.
* Jquery is in node_modules folders.

## Extra Help
**You can enter your codes in the section:**
```
    <!--Info-->
        <section>
            -CODING HERE-
        </section>
    <!--End Info-->
```
**Spinners have animation delay. If you don't like delay, disable or delete them (line 8 to 15):**
```
        <style>
            .animation1{
                animation-delay: 0.1s !important;
            }
            .animation2{
                animation-delay: 0.2s !important;
            }
        </style>
```
**If you want this that loading fade out after load the page, uncomment line 45 to 50 or use the following command:**
```
        <script src="node_modules/jquery/dist/jquery.min.js"></script>
        <script>
          $(document).ready(function () {
            $("#Loading").fadeOut();
          });
        </script>
```