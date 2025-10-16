# Dog-Cat-Image-Classification
In This Project I Create And Compare 3 Models For Image Classification. A General Purpose Simple CNN Model, The CNN Model Optimized For Dog And Cat Images And Lastly A Fine tuned Transfered MobileNetV2 for Dog And Cat Images

The Code Consist Of One Dataset Called Cifar10 From keras And 3 ANN Models To Determine How We Can Enhance Accuracy Of a Model.

<img width="472" height="79" alt="cifar10DogCat" src="https://github.com/user-attachments/assets/9c11bdb0-73ed-450b-ae0d-e9d60ed45033" />

First Model Is A General Purpose Simple CNN Model That You Can Find On Tensorflow Webstie.
It Will Train And Validate On All Cifar10 Images.

The Second Model Is Same CNN Model Optimized For Dog And Cat Images.
Meaning It Only Gets Cifar10 Cat And Dog Images For Input And Has Only Two Categories For Output.

Lastly A Fine tuned Transfered MobileNetV2 for Dog And Cat Images.
We Add A Layer For Upscaling Our Input Images To 128*128 To Match Dataset Requirement
And We Add An Output Layer To Tuning It For Dog And Cat Classification.

<img width="567" height="438" alt="download" src="https://github.com/user-attachments/assets/ac13cb34-de20-4ef5-8443-2e25775335c0" />

As You Can See The Result With Each Model Has Been Improved.(However The First Model Has Different Dataset Than Other Models)

You Can Run This Code On Google Collab.
