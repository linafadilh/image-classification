# image-classification
Proyek ini mmenggunakan dataset Intel Image Classification dari Kaggle yang berisi gambar pemandangan alam. Terdapat 8096 gambar pada dataset tersebut yang terbagi menjadi empat kelas yaitu glacier, mountain, sea, dan street.  

Dataset berhasil dibagi dengan rasio 80:20, menghasilkan 6476 gambar untuk train set dan 1620 gambar untuk test set.

Menggunakan Model CNN dengan empat lapisan Conv2D dan MaxPooling2D dan pada tiap bloknya, setelah itu menggunakan Flatten untuk meratakan output pada keempat blok tersebut. Anda menambahkan fully connected layer Dense dengan 512 neuron serta dropout sebesar 50% untuk mencegah overfitting.

Pada notebook yang anda submit, akurasi akhir yang anda peroleh berdasarkan evaluasi model adalah 92.22% untuk train dan 92.16% untuk validation.

Anda juga menampilkan plot akurasi dan loss model saat training.

Model anda berhasil disimpan dalam format SavedModel, TF-Lite, dan TFJS.

Mengimplementasikan beberapa callback, seperti ModelCheckpoint, EarlyStopping dan ReduceLROnPlateau.

Berhasil melakukan inference atau test menggunakan model TFLite.
