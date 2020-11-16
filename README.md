# hello-world
Создайте проект с указанным выше классом CustomMath. Уберите из метода main класса CustomMath проверку функции sum.
Уберите из метода testSum вызов метода fail. Убедитесь в прохождении теста функцией sum при текущих исходных данных.
 
public class CalculatorTest {
 @Ignore("Not running ")
 @Test
Проектирование и эксплуатация информационных систем в медиаиндустрии
Сиренко А.В. 2010
 public void testTheWhatSoEverSpecialFunctionality() {
 }
}


Включите игнорирование теста testMain. 
Исключения могут быть правильным поведением метода при определенных
условиях ( например, исключение отсутствия файла в случае, если он не доступен ).
Можно обрабатывать исключение в тесте с помощью блока try…catch(), либо передавать
его далее с помощью ключевого слова throws в описании метода.


Модифицируйте тест testDivision следующим образом:
static void assertArrayEquals(byte[] expecteds, byte[] actuals)
 Asserts that two byte arrays are equal.
static void assertArrayEquals(char[] expecteds, char[] actuals)
 Asserts that two char arrays are equal.
static void assertArrayEquals(int[] expecteds, int[] actuals)
 Asserts that two int arrays are equal.
static void assertArrayEquals(long[] expecteds, long[] actuals)
 Asserts that two long arrays are equal.
static void assertArrayEquals(java.lang.Object[] expecteds,
java.lang.Object[] actuals)
 Asserts that two object arrays are equal.
static void assertArrayEquals(short[] expecteds, short[] actuals)
 Asserts that two short arrays are equal.
static void assertArrayEquals(java.lang.String message, byte[] expecteds,
byte[] actuals)
 Asserts that two byte arrays are equal.
static void assertArrayEquals(java.lang.String message, char[] expecteds,
char[] actuals)
 Asserts that two char arrays are equal.
static void assertArrayEquals(java.lang.String message, int[] expecteds,
int[] actuals)
 Asserts that two int arrays are equal.
static void assertArrayEquals(java.lang.String message, long[] expecteds,
long[] actuals)
 Asserts that two long arrays are equal.
static void assertArrayEquals(java.lang.String message,
java.lang.Object[] expecteds, java.lang.Object[] actuals)
