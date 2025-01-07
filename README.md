# Classiq_QC
![image](https://github.com/user-attachments/assets/af2d9e34-b8d8-492d-8d0f-4805654a4264)

![image](https://github.com/user-attachments/assets/bb1f5507-76c0-4036-abc5-3757bcc54a68)

analyzer = Analyzer(circuit)
analyzer.plot_hardware_comparison_table(providers=["Azure Quantum", "IBM Quantum"])

![image](https://github.com/user-attachments/assets/4c3c6ad6-dd14-41c8-ac67-6d5ae2546986)

![image](https://github.com/user-attachments/assets/8aed0e66-9bd7-4212-82c3-eca06fa0d35c)

![image](https://github.com/user-attachments/assets/4098ec43-beaf-4f85-8965-f478848dad3a)

# Grover's Circuit - Secret Santa
You will now create and execute a circuit that will solve a SAT problem.

The problem is a Secret Santa problem these are the rules:
you will have 3 players, they all put their name on a piece of paper. All pieces of paper go into a large bowl and are shuffled.
Then each person will pick a piece of paper, if someone has their own name everything will start over.
In the end everyone has someone else's name and we can start the secret santa night.
Can you solve this problem using the `Grover` function documented in our [user guide](https://docs.classiq.io/latest/user-guide/grover-search/)?

Below there are various hints that can help you, click on them to expand.


You can look at the problem like this:

|Player|Ali|Berta|Charley|
|---|---|---|---|
|Ali|-|x1|x2|
|Berta|x3|-|x4|
|Charley|x5|x6|-|

Steps how to solve:
1. Create a SAT expression for this problem
2. Load the SAT expression in a `Grover` function
3. Execute the function and see the result

4. 
