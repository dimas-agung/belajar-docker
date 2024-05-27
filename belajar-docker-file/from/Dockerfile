FROM alpine:3
# run ketika docker build jalan
RUN mkdir hello
# msukkan kata hello ke file hello/word.txt
RUN echo "Hello" > "hello/world.txt" 
# command ketika container dijalankan
# tampilkan isi file
CMD cat "hello/word.txt"

# label digunakan hanya untuk menyimpan informasi, ext : nama author
LABEL author="Dimas Agung Setyobudi" from="Indonesia"


