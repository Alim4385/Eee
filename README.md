class Car:
    def __init__(self, brand, model, year):
        self.brand = brand
        self.model = model
        self.year = year
        self.speed = 0

    def accelerate(self, increment):
        self.speed += increment
        print(f"The car is now going at {self.speed} km/h.")

    def brake(self, decrement):
        self.speed -= decrement
        if self.speed < 0:
            self.speed = 0
        print(f"The car is now going at {self.speed} km/h.")

    def honk(self):
        print("Honk! Honk!")

# Araba nesnesi oluşturuluyor
my_car = Car("Toyota"

