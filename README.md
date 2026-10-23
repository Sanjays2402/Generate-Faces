# 🧑 Generate Faces — DCGAN

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

Generate new, realistic human faces using a **Deep Convolutional Generative Adversarial Network (DCGAN)** trained on the CelebA dataset. Part of the **Udacity Deep Learning Nanodegree** program.

## 📖 About

In this project, a DCGAN is defined and trained on a dataset of faces. The goal is to get a generator network to generate new images of faces that look as realistic as possible — similar to [thispersondoesnotexist.com](https://www.thispersondoesnotexist.com/).

The trained generator produces fairly realistic faces with small amounts of noise.

## ✨ Features

- 🧠 **DCGAN Architecture** — Deep Convolutional GAN for face generation
- 🎭 **CelebA Dataset** — Trained on celebrity face images
- 📓 **Full Notebook** — Complete training pipeline with visualizations
- ✅ **Unit Tests** — Included for model validation

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/Sanjays2402/Generate-Faces.git
cd Generate-Faces
conda create --name face_generation python=3.6
conda activate face_generation
conda install pytorch -c pytorch
pip install torchvision
pip install -r requirements.txt
```

### Run

Open `dlnd_face_generation.ipynb` in Jupyter Notebook.

## 📁 Project Structure

```
├── dlnd_face_generation.ipynb   # Main training notebook
├── dlnd_face_generation.html    # Exported notebook
├── problem_unittests.py         # Unit tests
└── requirements.txt             # Dependencies
```

## 👤 Author

**Sanjay Santhanam**

---

⭐ Star this repo if you found it useful!

## Terms & Disclaimer

By using this project you agree to the following.

- **No warranty.** This software is provided "as is", without warranty of any kind, express or implied, including merchantability, fitness for a particular purpose, and non-infringement.
- **No liability.** To the maximum extent permitted by law, the author and contributors are not liable for any claim, loss, or damage (direct, indirect, incidental, or consequential, including lost data or profits) arising from its use.
- **Your responsibility.** You use it at your own risk and are responsible for complying with the laws that apply to you.
- **AI output.** Generated content can be inaccurate, biased, or offensive. Review it before relying on or sharing it. Third-party AI providers or models you use process your input under their own terms.
- **Model results.** Models are trained for learning and research, may be inaccurate or biased, and are not validated for real-world decisions about people.
- **Coursework.** This was built for a course or program. Starter code, project specifications, and datasets may belong to the course provider and are included only for learning. Not affiliated with or endorsed by the provider. If you are taking the same course, follow its academic-integrity rules; do not submit this as your own work.
- Generated faces are synthetic. Do not use them to impersonate anyone, create fake identities, or mislead people. The CelebA dataset is licensed for non-commercial research only.
- **Third parties.** Names, logos, APIs, and services of others belong to their owners and are used for identification only; no affiliation or endorsement is implied.
- **Your statutory rights.** Nothing here limits rights that cannot be waived by agreement, including under consumer-protection laws in the USA, Canada (including Quebec), and India (Consumer Protection Act, 2019).
- **License.** Use, copying, and distribution are governed by the [LICENSE](LICENSE) file; if anything here conflicts with it, the license controls.

## Content, Assets & Fair Use

- **Original work.** Unless noted otherwise (including below), the code, text, design, and images in this repository were created by the author.
- **Libraries, fonts, and icons.** Third-party libraries, fonts (for example Google Fonts), and icon sets belong to their creators and are used under their own licenses; see the dependency manifests and each source for terms.
- **Logos, brands, and screenshots.** Third-party names, logos, and screenshots appear only to identify or describe their products (nominative use). They remain the property of their owners and do not imply affiliation or endorsement.
- **Ideas and inspiration.** Where this project is inspired by another product, game, or idea, it is an independent implementation. It borrows only general ideas, mechanics, or styles, which are not anyone's exclusive property, and is meant to contain no third-party code or artwork used without permission.
- **Datasets.** Datasets belong to their publishers and are used under their licenses or terms for learning and research. They may be excluded from the repository; get them from the original source and follow its license.
- **AI-generated content.** Some outputs are produced by AI models. They may resemble existing works by chance; check them before any public or commercial use.
- **Fair use and fair dealing.** Any third-party material is used in limited ways for purposes such as education, research, review, commentary, or identification, relying on fair use in the USA (17 U.S.C. § 107), fair dealing in Canada (Copyright Act, ss. 29–29.2), and fair dealing in India (Copyright Act, 1957, s. 52), where they apply.
- **Concerns and takedown requests.** If you own rights in something here and believe it is used improperly, [open an issue](https://github.com/Sanjays2402/Generate-Faces/issues) or contact the author through their GitHub profile with a link to the material and your claim. It will be reviewed promptly and credited, changed, or removed as appropriate. You may also use GitHub's DMCA process.
- **Contributions.** By contributing, you confirm you have the right to submit your contribution and agree it is licensed under this repository's license.
