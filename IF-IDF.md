# 介绍TF-IDF
## tf-idf用于评估字词在文件库的某一文件中重要程度
1.  文件j中词i的tf (term frequency):
     <div align=center>      <a href="https://www.codecogs.com/eqnedit.php?latex=tf_i_j&space;=\frac{n_i_j}{\sum_{k}&space;n_k_j}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?tf_i_j&space;=\frac{n_i_j}{\sum_{k}&space;n_k_j}" title="tf_i_j =\frac{n_i_j}{\sum_{k} n_k_j}" /></a>
2. 词i在文件库中的idf (inverse document frequency): 
       <div align=center>    <a href="https://www.codecogs.com/eqnedit.php?latex=idf_i&space;=&space;\log_1_0&space;\frac{|D|}&space;{&space;|\{j:&space;t_i\in&space;d_j\}&space;|&space;&plus;&space;1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?idf_i&space;=&space;\log_1_0&space;\frac{|D|}&space;{&space;|\{j:&space;t_i\in&space;d_j\}&space;|&space;&plus;&space;1}" title="idf_i = \log_1_0 \frac{|D|} { |\{j: t_i\in d_j\} | + 1}" /></a>
3. 词i的tfidf:
      <div align=center> <a href="https://www.codecogs.com/eqnedit.php?latex=tfidf_i&space;=&space;tf_i,&space;_j&space;*&space;idf_i" target="_blank"><img src="https://latex.codecogs.com/gif.latex?tfidf_i&space;=&space;tf_i,&space;_j&space;*&space;idf_i" title="tfidf_i = tf_i, _j * idf_i" /></a>
     
