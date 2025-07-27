How to use the script.

!python labelme2coco2017.py \
            --dataset_type labelme \
            --json_input_dir /data/wuxin/ntc_data0316/ann/ \
            --image_input_dir /data/wuxin/ntc_data0316/png/ \
            --output_dir ./ntc_new_coco4 \
            --train_proportion 0.8 \
            --val_proportion 0.2 \
            --test_proportion 0.0
