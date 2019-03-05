Parameters:
    Number of commands = 28
    Number of semantic descriptors = 55
    Number of subjects = 9

Files:
    1. 'command_names.xlsx'
        * This file contains the command ids and the names of the 34 commands
    2. 'semantic_descriptors.xlsx'
        * This file contains the descriptor ids and the names of the 55 semantic descriptors
    3. 'semantic_description_matrix.mat'
        * This mat file contains three variables:
            I. 'context_modifier_sd_matrix': A three dimensional (34 x 55 x 9) matrix.
                Each row is a combined semantic description of both the context and the modifier gesture.
                (i, j, k) corresponds to the ith command, jth semantic descriptor and kth subject
            II. 'context_sd_matrix': A three dimensional (34 x 55 x 9) matrix.
                Each row is a semantic description of the context of the gesture.
                (i, j, k) corresponds to the ith command, jth semantic descriptor and kth subject
            III. 'modifier_sd_matrix': A three dimensional (34 x 55 x 9) matrix.
                Each row is a semantic description of the modifier of the gesture.
                (i, j, k) corresponds to the ith command, jth semantic descriptor and kth subject
