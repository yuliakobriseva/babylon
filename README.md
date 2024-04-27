# babylon
class BabylonTower:
    def __init__(self, name, height_meters, location):
        self.name = name
        self.height_meters = height_meters
        self.location = location

    def display_info(self):
        print("Babylon Tower Information:")
        print(f"Name: {self.name}")
        print(f"Height: {self.height_meters} meters")
        print(f"Location: {self.location}")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the BabylonTower class
    babylon_tower = BabylonTower(name="Tower of Babel", height_meters=90, location="Babylon, Mesopotamia")

    # Displaying information about the Babylon Tower
    babylon_tower.display_info()
