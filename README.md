# Lab5_202001409

<h3>
  Name: Kashyap Panchani
  
  Id: 202001409
</h3>

<b>
<i>

Statis analysis checker used here is mypy.

</i>
</b>

The file used for purpose of static checking is code.py, which is also present in the repo by the same name. These are the screenshots of the errors that were generated(click on images to view more clearly):

<section>
<h2>

Error-1: 

</h2>

<b>False Negative:</b> library not found, even when it is actually installed.



![image](https://user-images.githubusercontent.com/84801087/227477458-616af62b-26a0-4541-bd08-ab4a24a8b4ce.png)

</section>

<section>

<h2>
Error-2:
</h2>


<b>Declaration of same function more than one time:</b> Function was first defined on line 28

![image](https://user-images.githubusercontent.com/84801087/227478384-57ec40e8-24fc-4501-8653-e5acfaaead1f.png)


line 28 where it is defined for the first time:

![image](https://user-images.githubusercontent.com/84801087/227478447-2a437860-3c9f-47de-bcfe-a060d6db626e.png)

</section>

<section>

<h2>
Error-3:
</h2>
<p>
<b>plt.subplots</b> was written as pltsubplots.
</p>

![image](https://user-images.githubusercontent.com/92992374/225272005-fe6f8375-d1ba-4665-a6a9-f61b0dae7689.png)

</section>


<section>

<h2>
Error-4:
</h2>
<p>
If statement was not intended properly
</p>

![image](https://user-images.githubusercontent.com/92992374/225273614-9a8b8ed8-688d-43e2-8f9b-29caf14bf45d.png)

</section>



<section>

<h2>
Error-5:
</h2>

<p><b>A colon</b> was missing</p>

![image](https://user-images.githubusercontent.com/75678658/225582455-3919d7ed-aa9d-483c-8bfe-65a77dbeafee.png)

</section>



<section>

<h2>
Error-6:
</h2>

<p> <b>Closing bracket</b> not found</p>

![image](https://user-images.githubusercontent.com/92992374/225282636-f07eeeb0-d5d0-4a3b-9204-beb9472aea1e.png)

</section>




