預設之dockerfile的問題是,
他在dockerfile中下載模型, 導致image有50gb
not fealing right

應是透過a1111/cache-sd-model.py


之後修改

現在可能連bindmount都有問題 且init可能也會因此比較慢



test prompt: photo of a rhino dressed suit and tie sitting at a table in a bar with a bar stools, award winning photography, Elke vogelsang