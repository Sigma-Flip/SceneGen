# SceneGen
Multi shot Scene generation

## Background

Recently, the field of video generation has made tremendous strides. Video generation techniques have improved video quality enhancement, frame interpolation, and consistent long-duration video synthesis across various applications. 

However, most existing models still generate video from a single viewpoint, and creating new viewpoints requires a new prompt. 

To overcome this limitation, our study proposes **scene-level multi-shot generation**, which does not produce video from a fixed viewpoint but instead naturally transitions across multiple viewpoints while remaining faithful to the given prompt.



<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/458c94e2-95be-4aa2-ae1b-c87de87a1df8" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/dadee034-0601-4f98-89af-7dad419ab49f" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/e9fee988-94c2-4da1-a3ec-1c2c4e59e222" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/1ad3d777-bccd-48b1-8378-918d72465187" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/15a96cb5-1749-4e8e-a568-ec01f62ac037" width="64" height="64" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/4e9d2e73-6a24-40f5-8d2a-4f6af0a4ae10" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/1c279dac-71f0-4f09-856f-7686568ea506" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/59694ed5-9f2f-429f-b6ce-73b72a536d0f" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/ed4389f6-af83-4c14-9723-217b489bb4d3" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/eb73ff31-9096-41e7-b4e7-a1236bfe389d" width="64" height="64" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e8e7e711-8c09-40ef-b4c1-d268f4ac0bde" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/b6a619c2-f55e-42cf-9093-5cb4abadcb03" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/acb18eba-f9bc-4673-865b-35d560dd56e5" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/5ed46f70-6636-4607-bb86-70c03df3040f" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/94566f2c-ed0a-44b1-a01e-72d157f59d3c" width="64" height="64" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/96acaaf0-2cf8-4353-b219-6bfd1f28a9ab" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/f8c0c964-9296-433d-9637-257f0fbc2762" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/a1d1c69a-f99b-4be7-b5e5-44aa86c48623" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/1178c210-bdcf-4213-b245-3386eada2ecc" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/4b720d17-bf4d-43cf-998f-e0664091a232" width="64" height="64" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/73a0bb6d-57f1-487d-9890-7f6582ac40c6" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/f4a15b47-19af-4c79-9f72-643e642edcc3" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/e631a9ee-8576-464b-8b60-de34cc96f370" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/d070efe4-2c47-4a87-bf21-a3bd68ebb9e4" width="64" height="64" /></td>
    <td><img src="https://github.com/user-attachments/assets/3a052f71-15d2-4b70-8358-6c0d146ac1d6" width="64" height="64" /></td>
  </tr>
</table>
