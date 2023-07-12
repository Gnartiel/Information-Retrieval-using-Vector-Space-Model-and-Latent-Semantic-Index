* Thư mục Code gồm có 6 file:

	- WhooshCranfield.ipynb: file chạy code với thư viện Whoosh và tập Cranfield

	- VectorSpaceChayLaiFull1400.ipynb: file chạy VSM và trả về 1400 kết quả với mỗi query với tập Cranfield

	- LSI_ThuNghiemSliceQuery.ipynb: file chạy LSI với thử nghiệm cắt ma trận với số chiều từ 100 đến 1400 để chọn ra một chiều cao nhất với tập Cranfield

	- LSI_ChayLaiSlice700.ipynb: file chạy LSI với số chiều 700 và trả về 1400 kết quả với mỗi query với tập Cranfield

	- Vector_Space_Corpus.ipynb: file chạy VSM và trả về 1400 kết quả với mỗi query của tập Corpus

	- WhooshCorpus.ipynb: file chạy code với thư viện Whoosh và tập Corpus

* Thư mục Doc chứa file báo cáo theo 2 dạng là .docs và .pdf

* Link data: trong các file code có link để download data từ drive, cụ thể:

	- Cranfield:
		+ TEST.zip: https://drive.google.com/file/d/1g0JYIiu-l6dSo5BpOuAeem2rVCkxNHjE/view?usp=drive_link
		+ Cranfield.zip: https://drive.google.com/file/d/1D48c_crSg6ia_OqZ5HoJmVmDLgn-iqq5/view?usp=drive_link

	- NFCorpus: 
		+ nfcorpus.tar.gz: https://drive.google.com/file/d/1QscBtuFj3XW7Gl3lhWdEx6r8Yit0yJ2v/view?usp=drive_link
		+ Sau khi giải nén file nén trên, nhóm sử dụng các file data gồm
			1. Docs là train.docs
			2. Danh sách các câu truy vấn là train.all.queries
			3. Danh sách các kết quả của câu truy vấn là train.3-2-1.qrel