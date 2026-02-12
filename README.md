# Aquatic Plant-Species-Image-Classification

Brief Description
This project is an image classification system that automatically identifies 20 different types of aquatic plants. Using a camera or uploaded image, the system recognizes plant species in seconds similar to how plant identification apps work.
The model was trained with 5,000 images (250 photos of each plant type) using Google's Teachable Machine platform. It can recognize plants from photos taken at different angles, lighting conditions, and growth stages.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e9b18656-4a1c-432e-afe0-e336ded7b3cf" />


**Model Has**<br>

Epoch: 50<br>

Batch Size: 16<br>

Learning Rate: 0.001<br>

"I chose 50 epochs because the model needs multiple passes through the dataset to learn the features of 20 different classes. A batch size of 16 was selected to balance training efficiency and generalization, ensuring the model updates weights frequently without overloading memory. The learning rate of 0.001 was used as it is a standard value for transfer learning, allowing the model to converge steadily without skipping over the optimal solution. These settings aim to maximize accuracy while minimizing overfitting."<br>

**“Under the Hood” Results**<br>

<img width="390" height="855" alt="image" src="https://github.com/user-attachments/assets/021e7eea-dd19-4ebc-9aa0-b2071375adfb" />

# Plant Species Section

| #  | Common Name            | Scientific Name             | Description                                                                                                                                                                                                |
| -- | ---------------------- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | **Water Lily**         | *Nymphaea* spp.             | Floating aquatic perennial with large, round leaves and showy flowers in white, pink, or yellow. Roots anchor in pond bottom while leaves and flowers float on surface.<br><br>.![image_1](https://github.com/user-attachments/assets/3c68266e-b788-4a1e-81a8-7e02e0a8f4aa)
.             |
| 2  | **Duckweed**           | *Lemna minor*               | Tiny free-floating aquatic plant consisting of 1-3 small oval leaves (fronds) less than 5mm wide. One of the smallest flowering plants, forms dense green mats on still water.<br><br>.![image_6](https://github.com/user-attachments/assets/ec367c3c-e8d1-44c9-a511-b22a8a7afd15)
.      |
| 3  | **Hydrilla**           | *Hydrilla verticillata*     | Submerged invasive aquatic weed with whorled leaves in groups of 4-5. Stems can grow 20-30 feet long, forms dense underwater mats that choke waterways.<br><br>.![image_7](https://github.com/user-attachments/assets/bcc5a525-9ca9-4965-b6fc-10cb0694ccb1)
.                             |
| 4  | **Water Lettuce**      | *Pistia stratiotes*         | Free-floating rosette of soft, fuzzy pale-green leaves resembling an open lettuce head. Roots hang submerged, reproduces rapidly in warm, nutrient-rich waters.<br><br>.![image_240](https://github.com/user-attachments/assets/b4560c1c-9b54-4190-b3f4-ca44e98627cc)
.                     |
| 5  | **Water Spinach**      | *Ipomoea aquatica*          | Semi-aquatic trailing vine with hollow stems and arrow-shaped leaves. Popular edible green in Southeast Asia, grows in moist soils or floating in water.<br><br>.![image_0](https://github.com/user-attachments/assets/3ea107fa-d99d-41b0-b90f-a12763c3d757)
.                            |
| 6  | **Arrowhead Plant**    | *Sagittaria latifolia*      | Emergent aquatic plant with distinctive arrow-shaped leaves and white three-petaled flowers. Also called duck potato, grows in shallow wetlands and pond edges.<br><br>.![image_0](https://github.com/user-attachments/assets/b6b27dfc-02f2-4524-b72e-13c6067ae4ae)
.                     |
| 7  | **Sea Lettuce**        | *Ulva lactuca*              | Bright green, translucent seaweed with thin, ruffled sheets resembling lettuce leaves. Found in marine intertidal zones worldwide, edible and high in minerals.<br><br>.![image_20](https://github.com/user-attachments/assets/0ebb8b37-fb9b-4ae8-9c23-8254c09ad2db)
.                     |
| 8  | **Kelp**               | *Macrocystis pyrifera*      | Giant brown seaweed forming massive underwater forests. Can grow up to 150 feet long with gas-filled bladders that keep fronds floating toward sunlight.<br><br>.![image_2](https://github.com/user-attachments/assets/a5c1dc63-36d1-467f-94ec-03cf04cf1ac4)
.                            |
| 9  | **Sargassum**          | *Sargassum* spp.            | Brown marine algae with branching, berry-like air bladders. Forms extensive floating mats in the Sargasso Sea, provides critical habitat for sea turtles and fish.<br><br>.![image_24](https://github.com/user-attachments/assets/5c7c026e-f4d8-44f3-a553-e2f195a505c3)
.                  |
| 10 | **Red Algae**          | *Rhodophyta* division       | Marine algae ranging from red to purplish-brown due to phycobilin pigments. Includes nori (sushi wrap) and Irish moss, found in deeper waters than green algae.<br><br>.![image_3](https://github.com/user-attachments/assets/4ab81893-dcde-4426-bb6f-98eebd0ec203)
.                     |
| 11 | **Water Hyacinth**     | *Eichhornia crassipes*      | Free-floating plant with thick, glossy round leaves and striking lavender-blue flowers with yellow markings. One of the world's fastest-growing plants, invasive in many regions.<br><br>.![image_10](https://github.com/user-attachments/assets/fdd5b424-6bf5-400b-b896-7e8e72b10bc7)
.   |
| 12 | **Salvinia**           | *Salvinia minima*           | Floating aquatic fern with small, oval leaves covered in water-repellent hairs. Forms dense mats that block sunlight, no true roots but modified leaf structures underwater.<br><br>.![image_30](https://github.com/user-attachments/assets/dd877b84-3090-49b5-bc7d-ca4f011f89b9)
.        |
| 13 | **Floating Pennywort** | *Hydrocotyle ranunculoides* | Aquatic perennial with round, penny-sized leaves on long stems floating on water surface. Invasive in many areas, can double its biomass in 3-5 days.<br><br>.![image_3](https://github.com/user-attachments/assets/b2dd8458-a4eb-4b94-ad45-64533cef8c6a)
.                               |
| 14 | **Yellow Water Lily**  | *Nuphar lutea*              | Aquatic plant with heart-shaped floating leaves and bright yellow cup-shaped flowers. Also called spatterdock, flowers rise slightly above water surface unlike white water lilies.<br><br>.![image_99](https://github.com/user-attachments/assets/454786e6-4473-4dce-8abe-13d6d4b6c058)
. |
| 15 | **White Water Lily**   | *Nymphaea alba*             | European native water lily with pure white fragrant flowers and large round floating leaves. Flowers open in morning and close in late afternoon.<br><br>.![image_3](https://github.com/user-attachments/assets/4f74267b-cc3f-4328-8e25-bfd05ca7a7a2)
.                                   |
| 16 | **Water Shamrock**     | *Marsilea quadrifolia*      | Aquatic fern with four-leaf clover appearance, leaflets folded at night. Grows in shallow water or wet mud, sporocarps resemble peppercorns.<br><br>.![image_11](https://github.com/user-attachments/assets/79042d0b-1724-4baf-98e7-1c5c6c01f985)
.                                        |
| 17 | **Amazon Sword**       | *Echinodorus grisebachii*   | Popular aquarium plant with large, sword-shaped bright green leaves. Native to South America, can grow 12-20 inches tall, excellent for aquarium backgrounds.<br><br>.![image_22](https://github.com/user-attachments/assets/422bc1f0-89bd-4dfc-ba6e-b2fd41058888)
.                       |
| 18 | **Java Moss**          | *Taxiphyllum barbieri*      | Dense, carpet-forming aquatic moss with tiny branching stems. Popular in aquascaping for creating lush green carpets and providing shrimp habitat.<br><br>.![image_6](https://github.com/user-attachments/assets/7842933a-3f56-4eb4-a6f5-29174a52ce54)
.                                  |
| 19 | **Anubias**            | *Anubias barteri*           | Slow-growing aquatic plant with dark green, heart-shaped leaves. Native to West Africa, thrives in low light, commonly attached to driftwood in aquariums.<br><br>.![image_28](https://github.com/user-attachments/assets/13e51414-fff8-4209-991e-fb50b1fee3ed)
.                          |
| 20 | **Giant Water Lily**   | *Victoria amazonica*        | World's largest water lily with leaves up to 10 feet diameter that can support 300+ pounds. Native to Amazon basin, white flowers that turn pink after pollination.<br><br>.![image_26](https://github.com/user-attachments/assets/23edd54a-2d2f-4124-8812-61830226fb2e)
.                 |

# Test the Model (Preview Section)

**TEST 1: WATER LETTUCE**
<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/55128d7a-cef6-4345-aaa7-8ec171eb27f2" />


**TEST 2: RED ALGAE**
<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/ef02c597-538a-498b-a080-1b0623ad8370" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/de2c5e60-16bd-47f7-af33-77a9097c0540" />

**TEST 3: YELLOW WATERLILY**
<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/2924ce33-326a-4fc8-996a-a64062bef281" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/f8184379-dc92-45f0-aef2-0576b761d638" />

**TEST 4: WATER SPINACH**
<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/1b6208c4-de07-4a21-ae74-679f4d0fa875" />

**TEST 5: ARROW HEAD PLANT**
<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/0cb56845-954e-4707-b874-7fa2eac3a831" />

**TEST 6: KELP**

<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/1b1e5ec1-985c-4cec-bc66-80c6b3c533c6" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/cfc811ec-8c94-4f89-a3e0-aca222bb0e23" />

**TEST 7: WATER HYACINTH**

<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/9807b858-d3c0-4ec2-be20-a66e6e5494f5" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/c0d992b7-56d5-49f0-8325-24f4e44e4ffa" />

**TEST 8: DUCK WEED**

<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/4288b79d-ce36-4d31-9105-32f76070015c" />

**TEST 9: SALVINIA**

<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/ac637226-7f58-4680-bb4b-a41fb6fbfe36" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/5f2ebfbb-c37f-4e19-872b-92d2b60f960f" />

**TEST 10: Floating Pennywort**

<br><br><img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/e2b823e6-e765-44e1-b370-67fff02c96ba" />
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/0d2846d8-1dbf-418f-8e1b-c7f5c40eb2d5" />




# Export the Model

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9035cfbf-ffe3-4bf9-80b6-3ce1e437a55e" />














