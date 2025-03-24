# 🚀 Portfolio Deployment Using GitHub Actions

This project automates the deployment of a portfolio website using **GitHub Actions** and **AWS S3**. Whenever new changes are pushed to the GitHub repository, a workflow is triggered that builds and deploys the updated website to the S3 bucket.

---

## 📌 Features
- **Continuous Deployment**: Automatically deploys changes to AWS S3 on every push to the `main` branch.
- **GitHub Actions Workflow**: Uses a CI/CD pipeline to build and deploy the website.
- **AWS S3 Static Hosting**: The website is hosted as a static site on an AWS S3 bucket.
- **Customizable Portfolio**: Easily update the content via GitHub commits.

---

## 🎯 Use Cases

1. **Automated Website Updates**: Any update to the GitHub repository (such as changing portfolio details or adding new projects) is automatically reflected on the live site without manual deployment.
2. **CI/CD for Static Websites**: This project serves as a great example of using **GitHub Actions** for automating static website deployment.
3. **AWS S3 as a Hosting Solution**: Demonstrates how to use **AWS S3 for hosting** and integrate it with GitHub Actions.
4. **Version Control & Rollbacks**: Since all changes are tracked in GitHub, you can easily rollback to a previous version in case of errors.
5. **Efficient Portfolio Management**: Developers, freelancers, and professionals can maintain their portfolio dynamically with minimal effort.
6. **Scalability & High Availability**: AWS S3 ensures high availability and scalability, making it a cost-effective solution for static sites.

---

## ⚙️ How It Works

1. Push changes to the GitHub repository.
2. GitHub Actions triggers a workflow to build and sync files with the AWS S3 bucket.
3. The updated website is deployed and accessible instantly.

---

## 🛠 Technologies Used

- **GitHub Actions** – For CI/CD automation
- **AWS S3** – For static website hosting
- **HTML, CSS, JavaScript** – Frontend technologies used for the portfolio
- **YAML** – Workflow configuration for GitHub Actions

---

## 🚀 Setup & Deployment

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Nikhil1422003/AWS-Portfolio.git
   ```

2. **Configure AWS Credentials in GitHub Secrets**
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`
   - `S3_BUCKET_NAME`

3. **Push Updates to GitHub**  
   Any changes committed to the repository will trigger the deployment workflow.

---

## 📜 License  
This project is open-source and available under the [MIT License](LICENSE).

### OUTPUT

![np17](https://github.com/user-attachments/assets/79086fc8-fe55-44fe-90c3-6855e4346223)

