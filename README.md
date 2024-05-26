Марио Боризовски 213246
![SILab2](https://github.com/MarioBorizovski/SI_2024_lab2_213246/assets/166833105/c6184a12-dbd5-4660-84ae-94472ec5db2e)

3. M = E - N + 2 
E - Број на ребра = 31
N - Број на јазли = 24
Цикломатската комплексност = 9

4.Тест случаи според Every Branch критериумот
	Тест Случај 1: allItems е null
	Тест Случај 2: allItems е празна листа
	Тест Случај 3: Item со name е null и barcode е валиден
	Тест Случај 4: Item со name е празен стринг и barcode е валиден
	Тест Случај 5: Item со name и barcode е валиден
	Тест Случај 6: Item со невалиден barcode
	Тест Случај 7: Item без barcode
	Тест Случај 8: Item со discount > 0 и price > 300 и barcode почнува со '0'

5.Комбинации
1.	True, True, True
Влез: item.getPrice() = 400, item.getDiscount() = 0.1f, item.getBarcode() = "012345"
Очекуван излез: Условот е вистинит, се одзема 30 од сумата.
2.	True, True, False
Влез: item.getPrice() = 400, item.getDiscount() = 0.1f, item.getBarcode() = "112345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
3.	True, False, True
Влез: item.getPrice() = 400, item.getDiscount() = 0.0f, item.getBarcode() = "012345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
4.	True, False, False
Влез: item.getPrice() = 400, item.getDiscount() = 0.0f, item.getBarcode() = "112345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
5.	False, True, True
Влез: item.getPrice() = 200, item.getDiscount() = 0.1f, item.getBarcode() = "012345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
6.	False, True, False
Влез: item.getPrice() = 200, item.getDiscount() = 0.1f, item.getBarcode() = "112345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
7.	False, False, True
Влез: item.getPrice() = 200, item.getDiscount() = 0.0f, item.getBarcode() = "012345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.
8.	False, False, False
Влез: item.getPrice() = 200, item.getDiscount() = 0.0f, item.getBarcode() = "112345"
Очекуван излез: Условот е лажен, не се одзема ништо од сумата.