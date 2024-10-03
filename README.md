# conda
(split -b 50M ....sh sh_chunk_)
cat sh_chunk_* > conda.sh
bash conda.sh
