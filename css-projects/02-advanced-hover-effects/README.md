# Advanced Hover Effects

![Output gif](https://raw.githubusercontent.com/im-ashish00/front-end-mini-projects/main/css-projects/02-advanced-hover-effects/assets/output.gif)

## Things Learned   
    
<details>
    <summary>How to make the whole thing responsive?</summary>
     &emsp;&emsp;Using variable and making rest of the stuff dependent on that one variable by performing calc on it.
</details>
<details>
    <summary>How to the make animations?</summary>
     &emsp;&emsp;Using before/ after psuedo elements and using the stacking context concept and setting the transition-origin or scaling it using transfrom depending on the requirements. Also, transition property takes other properties as a first thing. It's kinda amazing how it can take multiple values separated by a comma.
</details>


<details>
    <summary>How to make the hover work when someone uses tab to navigate?</summary>
     &emsp;&emsp;Using focus psuedo class.
</details>

<details>
    <summary>How to show the text before the background color of hover?</summary>
     &emsp;&emsp;Used before psuedo element so by lowering the z-index than the z-index of actual div element. Change the default stacking context to make it work.
</details>