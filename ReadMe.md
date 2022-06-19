#Patika.dev <a href="https://app.patika.dev/"> Patika.Dev 
#Patika.dev <a href="https://app.patika.dev/mertanildk"> mertanildk
<b> <h2> Insertion Sort Projesi </h2> </b>

 <b> 1. Madde <p> </b> <em> "[22,27,16,2,18,6] dizinin sort türüne göre aşamalarını yazınız" </em>
  <table border=5  cellpadding=15 cellspacing=10>
<th colspan=4> [22,27,16,2,18,6] dizisinin sort türüne göre aşamaları </th>

<tr>
<td align=center> 1 </td>
<td align=center> [**2**,27,16,22,18,6] </td> 

</tr>
<tr>
<td align=center> 2 </td>
<td align=center> [2,**6**,16,22,18,27] </td>

</tr>
<tr>
<td align=center> 3 </td>
<td align=center> [2,6,**16**,18,22,27] </td>

</tr>
<tr>
<td align=center> 4 </td>
<td align=center> [2,6,16,**18**,22,27] </td>

</tr>
<tr>
<td align=center> 5 </td>
<td align=center> [2,6,16,18,**22**,27] </td>

</tr>
</table>
  <hr>
 <b> 2. Madde <br> </br> </b> <em> "[22,27,16,2,18,6] Big-O gösterimi: " </em> <br> </br>
  Insertion sort'un Big o gösterimi: O(n<sup>2</sup>). Liste 6 elemanlı olduğundan  O(6<sup>2</sup>)=36 olacaktır.
<hr>
 <b>  3. Madde  <br> </br> </b> 
  <em> "Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması,
    **Best case**: Aradığımız sayının dizinin en başında olması.
    **Insertion Sort :** En basit sortin algoritmalarından biridir.
Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. İkinci en küçük elemanı buluyor ve 2. sıra ile yer değiştiriyor. Baktın ki ikinci sıradaki eleman en küçük dokunma!!! Hemen 3. sıraya geç. 4, 5 derken dizi bitti. İşte insertion sortun temel çalışma prensibi bu.

**Big-O Notation :** Bir algoritmanın performansını ve time complexitysini hesaplamak için kullanılır.     

**Time Complexity :** Bir algoritmanın çalışması için gerekli olan süredir. Ancak buradaki süre, saniyeleri hesaplayarak değil, kaç tane işlem gerçekleştirdiğine göre hesaplanmaktadır. Uygulama tarafından gerçekleştirilen işlem sayısı, veri setinin büyüklüğüne ve o veri setindeki elemanların sırasına göre belirlenir." </em>
 <hr>
<b>  4. Madde  <br> </br> </b> <em> "[22,27,16,2,18,6] Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız." </em> <br> </br>
  Dizi sıralandıktan sonra 18 sayısı ortada olacağından <b> Average Case </b> kapsamındadır.
 
 <hr>
 <b> 5. Madde </b>  <br> </br>
 <em> "[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız." </em> <p>
 <table border=5  cellpadding=15 cellspacing=10>
<th colspan=4> [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı </th>

<tr>
<td align=center> 1 </td>
<td align=center> [2,3,5,8,7,9,4,15,6] </td> 

</tr>
<tr>
<td align=center> 2 </td>
<td align=center> [2,3,4,8,7,9,5,15,6] </td>

</tr>
<tr>
<td align=center> 3 </td>
<td align=center> [2,3,4,5,7,9,8,15,6] </td>

</tr>
<tr>
<td align=center> 4 </td>
<td align=center> [2,3,4,5,6,9,8,15,7] </td>

</tr>
</table>

