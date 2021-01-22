# Folder organization
Top level are model folders, within each model folder are its implementations on different systems.

Note: Each implementaion must have train.py to drive the training process, which must accept argparse style arguments similar to run_exp.py.

# Preprocess data
TODO

# Usage
Use python run_exp.py --models a b --systems g h --gpu x --epochs xxx to run models a, b on system  g, h  respectively.

Note: If you would like to enumerate different configurations, you could specify them in the constructor of the corresponding Exp class (defined in run_exp.py) by writing a different create_exp_list function.
