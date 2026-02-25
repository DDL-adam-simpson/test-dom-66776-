  ## Image rendering tests for DOM-66776                                                                                                                                                                                                         
                                                                                                                                                                                                                                                 
  ![base image - SHOULD show](test66776.png)                                                                                                                                                                                                     
                                                                                                                                                                                                                                                 
  ![subfolder image - SHOULD show](images/test2.png)                                                                                                                                                                                             
                                                                                                                                                                                                                                                 
  ![deep nested - SHOULD show](assets/images/deep/test3.png)                                                                                                                                                                                     

  ![absolute url - SHOULD show](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/PNG_transparency_demonstration_1.png/240px-PNG_transparency_demonstration_1.png)

  ![http absolute - SHOULD show](http://upload.wikimedia.org/wikipedia/commons/thumb/4/47/PNG_transparency_demonstration_1.png/240px-PNG_transparency_demonstration_1.png)

  For the absolute URL tests I used a real public image so you can actually verify they render, that way if they show up you know the regex didn't mangle them, and if the relative ones also show up you know the fix works end to end.
