# comp90086-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COMP90086 Assignment 2 Solved](https://www.ankitcodinghub.com/product/comp90086-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101965&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90086 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you will use CNNs to classify a yoga pose dataset, yoga32. This dataset, based on a dataset created by Anastasia Marchenkova, includes 590 RGB colour images from 10 classes. Images have been downsampled to 32×32 pixels. We have provided a train/test split with 520 images for training/validation and 70 for testing – you should use the provided split throughout this assignment.

</div>
</div>
<div class="layoutArea">
<div class="column">
1. CNN implementation [3 pt]

</div>
</div>
<div class="layoutArea">
<div class="column">
1.1. Basic architecture [1 pt]

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Network diagram

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement the CNN architecture shown above in Figure 1. Use ReLU activation functions for all lay- ers except the final layer, which should use the Softmax activation function. Use the Adam optimiser and SparseCategoricalCrossentropy loss. Train this on the yoga32 dataset – what do you observe?

1.2. Regularisation and data augmentation [2 pt]

Modify the basic architecture by adding some form of (a) regularisation and (b) data augmentation. Train your new network on the yoga32 dataset – how does the training performance change?

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Your write-up should include a brief description and justification of your choice of regularisation and data augmentation schemes. It should also show the plots of training and validation accuracy for the original network (without regularisation+data augmentation) and the network with these modifi- cations and explain any differences that you observe in the training behaviour.

2. Error analysis [2 pt]

Evaluate your network from part 1.2 on the yoga32 test set. In your write-up, present the overall clas- sification accuracy and the average accuracy for each of the 10 classes. Explain the performance of the CNN model, using example images from the test set to illustrate your discussion. What classes/images were difficult for this model, and why?

3. Visualisation [2 pt]

Visualise the feature space that your network uses to classify images by implementing a nearest neigh- bour analysis. Use the embeddding from the last convolutional layer of your network from part 1.2 after it has been maxpooled (e.g., extract this layer at the point at which it is flattened and sent to the classification layer). To visualise how images are organised in this feature space, implement a nearest neighbour analysis. For each test image, find the 5 nearest neighbours in the training set. Use Eu- clidean distance to compare the feature vector from the test image to the feature vectors of the training images. In your write-up, show nearest neighbours for multiple test images to illustrate the feature space and explain your model’s performance. Critically evaluate your model – has it learned a good feature space for this classification task?

Submission

You should make two submissions on the LMS: your code and a short written report explaining your method and results. The response to each question should be no more than 500 words.

Submission will be made via the Canvas LMS. Please submit your code and written report sepa- rately under the Assignment 2: Code and the Assignment 2: Report links on Canvas.

• Your code submission should include the Jupyter Notebook (please use the provided template) with your code and any additional files we will need to run your code, if any (do not include the yoga32 dataset).

• Your written report should be a .pdf with your answers to each of the questions. The report should address the questions posed in this assignment and include any images, diagrams, or tables required by the question.

Evaluation

Your submission will be marked on the correctness of your code/method, including the quality and efficiency of your code and the appropriateness of design decisions. You should use built-in Python functions where appropriate and use descriptive variable names. Your written report should clearly ex- plain your approach and any experimentation used to produce your results, and include all of the spe- cific outputs required by the question (e.g., images, diagrams, tables, or responses to sub-questions).

</div>
</div>
</div>
