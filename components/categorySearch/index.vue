<template>
  <div class="relative w-1/3 group">
    <div>Category</div>
    
 
      <div class="absolute hidden group-hover:block p-10 transition duration-300">
        <div class=" grid grid-cols-2 w-full z-50 bg-white  gap-10">
      <div class="flex flex-col">
        <h2 class="text-slate-600">Home Types</h2>
        <ul>
          <li v-for="home in  homeTypes" :key="home.type">
        {{ home.type }}
      </li>
        </ul>
      </div>
      <div class="flex flex-col">
        <h2 class="text-slate-600">Home Location</h2>
        <ul>
          <li v-for="location in Towns" :key="location">
          {{ location }}</li>
        </ul>
      </div>
   
    </div>
  </div>

  </div>
</template>




<script>
export default {
  data() {
    return {
      homeTypes:[
    {"type": "Villa", "description": "A luxurious and spacious private residence with high-end amenities, often featuring a large yard or garden.", "features": ["Luxury", "Privacy", "Spacious"]},
    {"type": "Apartment", "description": "A self-contained living space in a larger building, typically offering modern amenities and convenient urban living.", "features": ["Contemporary", "Urban Living", "Shared Facilities"]},
    {"type": "Condominium", "description": "A housing unit within a larger complex, combining the privacy of a home with shared amenities like gyms, pools, and common areas.", "features": ["Community Living", "Amenities", "Security"]},
    {"type": "Service for Student", "description": "Housing services tailored for students, providing affordable and convenient accommodations with a focus on academic environments.", "features": ["Student-Friendly", "Affordable", "Academic Support"]},
    {"type": "Traditional Ethiopian Home", "description": "Experience the rich cultural heritage with a traditional Ethiopian home, featuring unique architectural elements and cultural aesthetics.", "features": ["Cultural Heritage", "Architectural Elements", "Cultural Aesthetics"]},
    {"type": "Luxury Villa", "description": "Enjoy spacious living and luxurious amenities in a private villa, offering a high-end and comfortable lifestyle.", "features": ["Luxurious", "Private", "Comfortable Living"]},
    {"type": "Modern Apartment", "description": "Choose a contemporary apartment with modern amenities and a convenient location for a cosmopolitan living experience.", "features": ["Contemporary", "Convenient Location", "Modern Amenities"]},
    {"type": "Townhouse", "description": "Select a townhouse for a balance of privacy and community living, often featuring multiple floors and a cozy neighborhood atmosphere.", "features": ["Privacy", "Community Living", "Multiple Floors"]},
    {"type": "Duplex", "description": "Experience the comfort of a duplex, offering two separate living spaces within the same building for added privacy and flexibility.", "features": ["Privacy", "Two Living Spaces", "Flexibility"]},
    {"type": "Bungalow", "description": "Enjoy single-story living with a charming bungalow, perfect for those seeking simplicity and easy access to all living spaces.", "features": ["Single-Story", "Charming", "Simplicity"]},
    {"type": "Gated Community House", "description": "Opt for a house in a secure gated community, providing a safe and peaceful environment with shared amenities for residents.", "features": ["Security", "Peaceful Environment", "Shared Amenities"]},
    {"type": "Rural Retreat", "description": "Escape to a peaceful rural retreat, surrounded by nature and tranquility, ideal for those looking for a serene living experience.", "features": ["Serene", "Nature Surroundings", "Tranquility"]}
],
Towns:[
    "Addis Ababa",
    "Dire Dawa",
    "Adama (Nazret)",
    "Mek'ele",
    "Bahir Dar",
    "Gondar",
    "Hawassa",
    "Jimma",
    "Dessie",
    "Harar",
    "Arba Minch",
    "Dilla",
    "Jijiga",
    "Shashamane",
    "Nekemte",
    "Debre Markos",
    "Sodo",
    "Gambela",
    "Robe",
    "Asosa"
]

    };
  },
};
</script>
