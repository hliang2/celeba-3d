CelebA-3D: A Large-Scale 3D In-the-Wild Face Dataset

Project Page | Paper (Coming Soon) | Dataset (Coming Soon)

Status: This repository currently hosts the source code for our project webpage preview. The full dataset, training code, and paper are in preparation and will be released soon.

Overview

CelebA-3D focuses on reconstructing high-fidelity 3D avatars from in-the-wild images with unprecedented detail and topological consistency. This dataset aims to bridge the gap between 2D in-the-wild portrait images and high-quality, animation-ready 3D assets.

News

[April 2026] Project webpage source code released.

[Coming Soon] Full dataset download links and API.

[Coming Soon] Pre-trained models and inference code.

[Coming Soon] Technical report and paper.

Key Features

High-Fidelity 3D Avatars: Accurately reconstructed meshes and textures from single 2D images.

In-the-Wild Diversity: Robust against diverse lighting conditions, extreme poses, and varied facial expressions.

Topological Consistency: All released meshes share a unified topology, making them immediately ready for animation and downstream graphics tasks.

Local Webpage Setup

To view and modify the project webpage preview locally:

Clone this repository:

git clone [https://github.com/your-username/CelebA-3D.git](https://github.com/your-username/CelebA-3D.git)
cd CelebA-3D


Add your input images to the images/ directory (e.g., 00000.jpg, 00001.jpg).

Add your rendered 3D avatar videos to the videos/ directory (e.g., 00000.mp4, 00001.mp4).

Open index.html in your web browser.

(Note: The page includes smart visual fallbacks, so you can safely test the layout even before your media files are fully rendered.)

Anticipated Structure

Once the full codebase is released, the repository will be structured as follows:

CelebA-3D/
├── dataset/            # Download scripts and dataset loaders
├── models/             # Network architectures and pre-trained weights
├── scripts/            # Training, inference, and evaluation scripts
├── images/             # Project page image assets
├── videos/             # Project page video assets
├── index.html          # Project webpage source
└── README.md


Citation

If you find our work, codebase, or dataset useful in your research, please consider citing our work once published:

@article{celeba3d2026,
  title={CelebA-3D: A Large-Scale 3D In-the-Wild Face Dataset},
  author={Doe, Jane and Smith, John and Johnson, Alice and Williams, Bob},
  journal={Coming Soon},
  year={2026}
}


License

The code and dataset will be released under a non-commercial research license. Full license details and terms of use will be provided alongside the data release.
