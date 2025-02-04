Commands:
   --lab_file="editing_final_lab.txt"
   
   lab_file → A shell variable.
   
  = → The assignment operator (no spaces before or after).
  
  "editing_final_lab.txt" → The string value assigned to the variable.

  ![lab3 1](https://github.com/user-attachments/assets/63c0a18b-2744-4733-9efa-8bf9f43859cd)


  --vim "$lab_file"
  
  vim → Launches the Vim editor.
  
  $lab_file → Expands to the value assigned to lab_file (e.g., "editing_final_lab.txt").
  
 " (Double Quotes) → Ensures the filename is treated as a single unit, even if it contains spaces.
 
![exp3 2](https://github.com/user-attachments/assets/0f1f005d-4b3d-4dd6-9377-c27cc503702b)

![exp3 3](https://github.com/user-attachments/assets/da01e142-045f-4c38-ba9e-73a4767af488)


--nano "$lab_file"
nano → Launches the Nano text editor.

$lab_file → Expands to the value of the lab_file variable (e.g., "editing_final_lab.txt").

" (Double Quotes) → Ensures the filename is treated as a single unit, even if it contains spaces.


![exp3 4](https://github.com/user-attachments/assets/e993245f-e811-4b9f-9fb0-c64ba83e25cd)


![exp3 5](https://github.com/user-attachments/assets/30b73744-73f6-491c-b2ca-dc918887e245)
