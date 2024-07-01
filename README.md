class CelestialObject:
    def __init__(self, name, description):
        self.name = name
        self.description = description

    def visit(self):
        print(f"Visiting {self.name}: {self.description}")

def main():
    # List of celestial objects to visit
    celestial_objects = [
        CelestialObject("Sun", "The star at the center of our solar system."),
        CelestialObject("Mercury", "The smallest planet in our solar system."),
        CelestialObject("Venus", "The second planet from the sun, with a thick, toxic atmosphere."),
        CelestialObject("Earth", "Our home planet, the third from the sun."),
        CelestialObject("Mars", "The red planet, known for its iron oxide surface."),
        CelestialObject("Jupiter", "The largest planet in our solar system."),
        CelestialObject("Saturn", "Known for its stunning ring system."),
        CelestialObject("Uranus", "An ice giant with a blue-green color due to methane."),
        CelestialObject("Neptune", "The furthest planet from the sun, known for its intense blue color."),
        CelestialObject("Pluto", "A dwarf planet in the Kuiper belt.")
    ]

    # Simulate the journey
    print("Starting Celestial Journey...\n")
    for obj in celestial_objects:
        obj.visit()
        print()

    print("Journey complete! Hope you enjoyed the trip through our solar system.")

if __name__ == "__main__":
    main()
