# satal/agency-swarm Docker Image 🌠

Welcome to `satal/agency-swarm-docker`, the Docker image that's your streamlined bridge to exploring the Agency Swarm project by VRSEN with ease and a bit of fun. Think of this image as your personal assistant into the world of Agency Swarm, designed to make your journey both enjoyable and efficient.

## Why Choose This Docker Image?

- **Ease of Use**: We've simplified the setup so you can dive straight into creating with Agency Swarm.
- **Flexibility**: The `/app` volume mapping lets you easily access your creations on your local machine.
- **Environment Ready**: Seamlessly integrate your `OPENAI_API_KEY` through an environment variable for a smooth experience.

## Getting Started

### Before You Begin

Ensure Docker is installed on your system. If it's missing, visit <a href="https://docs.docker.com/get-docker/">Docker's official website</a> for guidance.

### Pulling the Docker Image

```
docker pull satal/agency-swarm
```

### Building the Docker Image 🏗
If you're adventurous and prefer to build the satal/agency-swarm Docker image from source, here's how you can do it. This is especially handy if you want to tweak the image or contribute to its development.

First, clone the repository that contains the Dockerfile:

```
git clone https://github.com/Satal/agency-swarm-docker.git
cd agency-swarm-docker
```

Then, build the image with:
```
docker build -t satal/agency-swarm .
```

This command tells Docker to build an image named satal/agency-swarm from the Dockerfile in the current directory (.). Once the build process completes, you'll have your very own Docker image ready to run, explore, and possibly even improve upon.

Remember, building your own image gives you the flexibility to modify and customize it to fit your needs, whether it's updating dependencies, changing the base image, or adding new scripts. Just make sure to keep an eye on the updates from the original Agency Swarm project to ensure compatibility.

### Running the Docker Container

Launch the container in interactive mode, map `/app` to your desired directory, and provide your OpenAI key:

```
docker run -it --rm -v <YourLocalDirectory>:/app -p 7680:7680 -e OPENAI_API_KEY=<YourOpenAIKey> satal/agency-swarm

# For example
docker run -it --rm -v ./work_dir:/app -p 7680:7680 -e OPENAI_API_KEY=<YourOpenAIKey> satal/agency-swarm
```

Make sure to replace <YourLocalDirectory> with your directory path and <OPENAI_API_KEY> with your actual OpenAI API key.

## Understanding Your Workspace

- **/app**: The heart of your project's output. This volume mapping ensures you have direct access to your generated work.

## Interactive Mode

Opting for interactive mode makes your session with Agency Swarm direct and engaging, enabling real-time interaction and output observation.

## Using --rm for Clean-up 🧹
When you run your Docker container with the `--rm` flag, you're ensuring that your Docker environment remains neat and tidy. This flag tells Docker to automatically remove the container once it's stopped. It's like having a self-cleaning workspace; once you're done with your Agency Swarm session, the container cleans up after itself, leaving no unnecessary digital footprint. This practice is particularly useful for keeping your system free of clutter and managing resources efficiently, especially when you're experimenting or developing in rapid iterations.

Here's how to use it:

```
docker run -it --rm -v <YourLocalDirectory>:/app -p 7680:7680 -e OPENAI_API_KEY=<YourOpenAIKey> satal/agency-swarm
```
By including --rm, you ensure that each session with Agency Swarm is as fresh as the first, without having to manually remove the container afterwards.

## Issue Reporting

- **Docker Image Queries**: Encounter an issue? Let us know right here in this repository.
- **Agency Swarm Questions**: For inquiries specific to Agency Swarm, the <a href="https://github.com/VRSEN/agency-swarm">VRSEN repository</a> is your go-to.

## A Little Love Goes a Long Way ❤️

Impressed by Agency Swarm? Drop a star on the <a href="https://github.com/VRSEN/agency-swarm">Agency Swarm repository</a> and show VRSEN some appreciation for their innovative project. It's a simple gesture that means a lot.

## License

Embark on your Agency Swarm adventure with peace of mind; both this Docker image and the Agency Swarm project are under the MIT License. Happy creating!
