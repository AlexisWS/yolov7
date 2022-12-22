# yolov7
From https://github.com/WongKinYiu/yolov7 (slightly changed to train a custom dataset)

Some changes:
yolov7/utils/loss.py: (line 1389, 1543, and 742) matching_matrix = torch.zeros_like(cost) to matching_matrix = torch.zeros_like(cost, device="cpu")
