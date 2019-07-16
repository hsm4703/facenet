Backtracking (last call last time):
The file "src / train_softmax.py", line 580, at
Master (parse_arguments(sys.argv [1:]))
File "src / train_softmax.py", line 234, in the main
In prelogits, prelogits_center_loss, args.random_rotate, args.random_crop, args.random_flip, prelogits_norm, args.prelogits_hist_max, args.use_fixed_image_standardization)
File "SRC / train_softmax.py", line 306, on the train
LR = facenet.get_learning_rate_from_file(learning_rate_schedule_file , epoch)
The file "C:\facenet-master \ src \ facenet.py", line 295, in get_learning_rate_from_file
e = int(par [0])
ValueError: Invalid text for int() with a base of 10: ''
e = int(par [0]) so how can I fix it?
