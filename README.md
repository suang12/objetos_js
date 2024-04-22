
                                PROPIEDADES DE NUMBER 

    
Las propiedades del NUMBER  en JavaScript son atributos estáticos del objeto Number que proporcionan información sobre los números en JavaScript. Las propiedades más comunes son:

MAX_VALUE: Representa el valor numérico máximo que se admite en JavaScript, aproximadamente 1.79E+308. Los valores mayores que MAX_VALUE se representan como Infinity.

MIN_VALUE: Representa el valor numérico positivo más pequeño que está más cerca de 0, pero no el número más negativo. Es aproximadamente 5e-324.

NEGATIVE_INFINITY: Representa el valor de infinito negativo.

POSITIVE_INFINITY: Representa el valor de infinito positivo.

EPSILON: Representa la menor cantidad positiva por la que se puede agregar a 1 sin cambiar el valor. Es aproximadamente 2.22e-16.

MAX_SAFE_INTEGER: Representa el entero seguro máximo en JavaScript (253 - 1).

MIN_SAFE_INTEGER: Representa el entero seguro mínimo en JavaScript (-(253 - 1)).





                                    METODOS 
    1. Métodos para comprobar el tipo de número:
    Number.isFinite(number): Comprueba si un número es finito. Devuelve true si el número es finito, false en caso contrario.
Number.isNaN(number): Comprueba si un número es NaN (No a Number). Devuelve true si el número es NaN, false en caso contrario.
Number.isInteger(number): Comprueba si un número es un entero. Devuelve true si el número es un entero, false en caso contrario.
Number.isSafeInteger(number): Comprueba si un número es un entero seguro. Devuelve true si el número es un entero seguro (representable sin pérdida de precisión), false en caso contrario.

2. Métodos para convertir números a cadenas:

number.toFixed(decimals): Convierte un número a una cadena con un número específico de decimales. El parámetro decimals opcional especifica el número de decimales que se desean mostrar.
number.toExponential(fractionDigits): Convierte un número a notación exponencial. El parámetro fractionDigits opcional especifica el número de dígitos significativos después del punto decimal en la mantisa.
number.toString(radix): Convierte un número a una cadena en la base especificada por radix. Por defecto, radix es 10 (base decimal).


3. Método para convertir valores a números:

Number(value): Convierte un valor a un tipo de número. Este método intenta convertir el valor dado a un número. Puede ser útil para asegurarse de que un valor se use como número en una operación.