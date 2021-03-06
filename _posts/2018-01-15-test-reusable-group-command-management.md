---
layout: page
title: "Group command management"
category: test
date: 2018-01-05 15:17:55
order: 4
---

### Create a group command

  Navigate to **Hiring sample** -> **Create Position Request CSHS** -> **Case1** to generate a group command.
 
  1. [Import hiring sample project.][1]
 
  2. Enter project dashboard.
  
  3. Click **Create Position Request CSHS** in left-side menu bar.
  
  4. Click **Case1**
  
  5. Click **Edit** button on the right of suite name.
  
      ![][test_group_command_caselist_table]
  
  6. Choose at least two continuous case steps to save as group command.
  
      ![][test_group_command_caselist_table2]
  
  7. Click **Save as Group Command** button.
  
  8. Fill group command name and description in the form.
  
      ![][test_group_command_save_form]
  
  9. Click **Save** button.
  
      Then **Group Command** and new group command you have created appear in left-side menu bar, and the case steps you have chosen follow new group command.  
  
      ![][test_group_command]
  
  10. Click **Exit Edit** button.
  
  **Notes**  
  You can also add group command through the custom command menu.     
    ![][test_group_command_add]
    ![][test_group_command_create] 

### Add group command

  You can add a group command when you want to add some steps which belongs to this group command.

  1. Click **Edit** button on the right of suite name.
  
  2. Click ![][test_case_step_add_button] button in the operation column of case step list table where you want to reuse a group command.
  
  3. Fill add case step form according to below table.
  
      Parameter           | Description       
    ----------------------|-------------------
      Command             | Reused group command name, in custom category
      Assignee            | BPM user who help you finish process
      comment             | Comment of command
  
      ![][test_group_command_add]
  
  4. Click **Add** button.
  
  5. Click **Exit Edit** button.
  
### Edit group command

#### Edit group command name and description

  1. Click **Group Command** in left-side menu bar.
  
  2. Click ![][test_group_command_edit_button] button on the right of group command name.
  
      ![][test_group_command_bar]
  
  3. Edit group command name and group command description.
  
      ![][test_group_command_edit_form]
  
  4. Click **Update** button.
  
#### Edit case steps of group command

  1. Click **Execute Custom._command\_name_ with parameters \{\{Parameters\}\}** in case step list or click command name in left-side menu bar.
  
  2. [Edit case steps.][2]
  
### Delete Group command

  1. Remove the command from test cases first.
  
     * Enter into case step list of every test case which includes the group command.
     * Click **Edit** button on the right of suite name.
     * Click ![][test_case_step_delete_button] button in group command row.
     * Click **Delete** in delete form.
     * Click **Exit Edit** button.
  
        ![][test_case_steps_edit]
  
  2. Click ![][test_group_command_delete_button] button on the right of group command name.
  
### Define Group parameter  

  1. Define the group parameter for the group command.
  
      * Click **Group Command** in left-side menu bar.
      * Click **Parameter** button on the top right of group command page.
      * Enter group parameter key,display name in the group parameter page.
      * Click **Add** button to add group parameter.
      * Click **Cancel** button to exit.
      
         ![][group_parameter_add]
     
   2. Bind group parameter for case step parameter.
   
       * Click ![][test_case_step_edit_button] button to edit case step.
       * Choose the parameter value from the  select box.                   
       * Click **Save** button to save the parameter.
       
          ![][group_parameter_save]
  3. Edit this group command parameter value in the case step.
     You can see **name** is defined in the group parameter will be acted as the parameter input for group command.
     ![][group_parameter_input]  
          
  
          
  
  [1]: test-import_execute-sample-test-project.html
  [2]: test-unit-test-case-management.html
  [test_group_command_caselist_table]: ../images/test/test_group_command_caselist_table.PNG
  [test_group_command_caselist_table2]: ../images/test/test_group_command_caselist_table2.PNG
  [test_group_command]: ../images/test/test_group_command.PNG
  [test_group_command_add]: ../images/test/test_group_command_add.PNG
  [test_group_command_create]: ../images/test/test_group_command_create.PNG
  [test_group_command_edit_button]: ../images/test/test_group_command_edit_button.PNG
  [test_group_command_delete_button]: ../images/test/test_group_command_delete_button.PNG
  [test_group_command_bar]: ../images/test/test_group_command_bar.PNG
  [test_group_command_edit_form]: ../images/test/test_group_command_edit_form.PNG
  [test_group_command_save_form]: ../images/test/test_group_command_save_form.PNG
  [test_group_command_add]: ../images/test/test_group_command_add.PNG
  [test_case_step_delete_button]: ../images/test/test_case_step_delete_button.PNG
  [test_case_step_add_button]: ../images/test/test_case_step_add_button.PNG
  [test_case_steps_edit]: ../images/test/test_case_steps_edit.PNG
  [group_parameter_add]: ../images/test/test_group_parameter_add.PNG
  [test_case_step_edit_button]: ../images/test/test_case_step_edit_button.PNG
  [group_parameter_save]: ../images/test/test_case_step_parameter_save.PNG
  [group_parameter_input]: ../images/test/test_case_step_parameter_input.PNG

