# Create-simpleArraySum
def simpleArraySum(ar):     return sum(ar)  if __name__ == "__main__":     n = int(input())  # Зчитуємо розмір масиву     ar = list(map(int, input().split()))  # Зчитуємо елементи масиву     result = simpleArraySum(ar)  # Обчислюємо суму     print(result)  # Виводимо результат
