# tfidf, kai, tfidf+kai/ one-hot, count 

train_x_size          1500    15000   15000   150000이상 -> 메모리 터짐

train_y_size          500     5000    5000

tfidf_dict_size       1000    1000    5000

kai_dict_size         1000    1000    5000

tfidf_sprs(onehot)    0.766   0.8266  0.8266

kai_sprs(onehot)      0.758   0.823   0.8254

tfidf+kai_sprs(onehot)   0.758   0.8224   0.826

tfidf_cnt(count)      0.764   0.8238  0.8238

kai_cnt(count)        0.76    0.8212  0.8242

tfidf+kai_cnt(count)  0.764   0.822   0.8228
