# K-means MapReduce 

## Implémentation de l'algorithme de clustering k-means en utilisant le framework MapReduce (Hadoop version 3.1.3).

**K-means (ou K-moyennes) :** C’est l’un des algorithmes de clustering les plus répandus. Il permet d’analyser un jeu de données caractérisées par un ensemble de descripteurs, afin de regrouper les données “similaires” en groupes (ou clusters).

**Le clustering K-means** est un type d'apprentissage non supervisé, qui est utilisé lorsque vous avez des données non étiquetées (c'est-à-dire des données sans catégories ou groupes indéfinis).

**Mapper** OUTPUT: <centroid,point>
<samp text-align="justify"> La clef c’est le point central du cluster auquel appartient le point de valeur, donc notre output
c’est : <centroid,point>. </samp>

**Combiner** INPUT: Mapper Output
|| OUTPUT:<centroid, string((sum of point)+(point count))

**Reducer** INPUT: Combiner Output 
|| OUTPUT: <new_centroid,count_of_current_unchanged_centroid_point>

## Guide pour Compiler et construire .jar manuellement sur la machine virtuelle Hadoop : 

https://www.mediafire.com/file/esgx0xzm2ftnl2h/Kmeans_MapReduce.pdf/file



## Assigned By

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/benjdiasaad">
          <img width="150" height="150" src="https://github.com/mohamedbiniz.png?v=3&s=150">
          </br>
          Mr Mohamed Biniz
        </a>
      </td>
    </tr>
  <tbody>
</table>
