# Transferable-Interactiveness-Network

Dạ thầy vô script/download_dataset.sh để tải Data với mấy file pretrained ạ

Em chỉ đang làm trên bộ HICO thôi ạ

Lệnh train bộ HICO:
python tools/Train_TIN_HICO.py --num_iteration 2000000 --model TIN_HICO_test

Lệnh test bộ HICO:
python tools/Test_TIN_HICO.py --num_iteration 1700000 --model TIN_HICO

Dạ lúc test xong nó sẽ tạo ra một file tên 1700000_TIN_HICO_0.8_0.3new_pair_selection_H2O2.pkl ở folder ~Result(folder này có khi tải các file pretrained về ạ), file này chứa các detection của các ảnh vừa test xong.

