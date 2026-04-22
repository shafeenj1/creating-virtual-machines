<p align="center">
<img width="1498" height="364" alt="image" src="https://github.com/user-attachments/assets/5fe64060-6a0a-4212-a514-d2eb49a78b9c"
"/>
</p>

<h1>Creating Virtual Machines (Azure)</h1>
This tutorial outlines the implementation of creating Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create a virtual machine on Microsoft Azure](https://www.youtube.com/watch?v=yvpoFQ_VAj0)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop

  

<h2>Operating Systems Used </h2>


- Windows 10/11

<h2> Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4
- Step 5
- Step 6
- Step 7
- Step 8

<h2>Deployment Steps</h2>

<p>
<img width="924" height="258" alt="image" src="https://github.com/user-attachments/assets/fbc8b3b0-3573-49e4-a19a-6d5cc27d0ac0"
"
"/>
</p>
<p>
^Step 1 - Please search "Virtual Machine" or "VM" on the search bar
</p>
<br />

<p>
<img width="386" height="154" alt="image" src="https://github.com/user-attachments/assets/44a20c0a-92a9-4540-931f-1abc0ba6a673"
"/>
</p>
<p>
^Step 2 Please press create and then press Virtual machine and we will get started on creating the virtual machine.
</p>
<br />

<p>
<img width="844" height="628" alt="image" src="https://github.com/user-attachments/assets/6e31ca94-65f1-4e1d-83c9-36748a9d4736"
"/>
</p>
<p>
^Step 3 Follow my screenshot. Creating a Resource group is optional. For “pay as you go” text is my subscription I created manually (you do need a subscription in order to use Microsoft Azure so please create a subscription and name it whatever you want and use it for your subscription). For region pick any region you want, keep in mind i live in the “US West” and it did not give me an option for the “image” section. So just trial and error with regions, I have picked Canada Central and it worked for me fine. For image please select either windows 10 or windows 11, whatever is popping up on your drop down menu. Everything else doesn’t need much explanation, just copy that from my screenshot.

</p>
<br />



<img width="806" height="747" alt="image" src="https://github.com/user-attachments/assets/11b70e35-9231-469f-b349-658e57a7a6de"
/>
</p>
<p>
^Step 4 For size you typically want to aim for “D2s_v3 2 vcpus” because it’s usually the cheapest but it is up to you individually. For the Administrator account please remember your Username and password. If you forget, no worries you can update it again in azure or refresh the page and start over at step 1, it also doesn't hurt to have a separate window to type your username or password so you don’t forget . Then below licensing there is usually a checkbox below that, please check because this will allow you to create the machine and finally press “Review + create.”
</p>
<br />


<img width="918" height="762" alt="image" src="https://github.com/user-attachments/assets/0b46c92a-e434-40bb-b11f-94a31587d965"
/>
</p>
<p>
^Step 5 Hopefully it should say “Validation passed.” If not, please start over. Once the validation has passed press “create.”
</p>
<br />




<img width="883" height="750" alt="image" src="https://github.com/user-attachments/assets/e0a66411-310a-4caf-9b46-b33b65458991"
/>
</p>
<p>
^Step 6 After you press create it will take a little bit of time to create the virtual machine. Once the virtual machine is created please go back to the search bar and search “virtual machine” or “vm” and then click on your virtual machine and you should similarly see my screenshot above.^
</p>
<br />


<img width="455" height="531" alt="image" src="https://github.com/user-attachments/assets/722364ac-8c60-4087-a4fd-ee119e831c3e"
/>
</p>
<p>
^Step 7 Please refer back to my previous screenshot in step 6 and copy the Primary NIC public IP. Now what you want to do is connect, copy and paste your Primary NIC public IP onto your remote desktop on your computer. For Mac users please search “windows app” in the app store and download it. After you download it please press “add pc” in the + sign and paste your Primary NIC public IP. Once you can see it, double click and type in your username and password. For Windows users please search “remote desktop connection” you should already have and follow the similar steps as what i explained for the mac. The screenshot provided above is my Mac.
</p>
<br />



<img width="945" height="529" alt="image" src="https://github.com/user-attachments/assets/b927a2f1-282a-452b-9b5a-4101d476fdc9"
/>
</p>
<p>
^Step 8 Congratulations! You have created a virtual machine! Please note you can close it out if you are done and make sure to either stop or delete your virtual machine in Azure. If you forget to do that, you will be charged! Also even if you stop it you will still be charged but not as much compared to leaving it running.
</p>
<br />

