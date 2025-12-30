# Meals App
### Search meals based on various way.

## Project Installations
<ul>
<li>Clone/download the repository.</li>
<li>Run <code>npm install</code></li>
<li>Copy <code>.env.example</code> to <code>.env</code></li>
<li>Run <code>npm run dev</code> to start the application <code>http://127.0.0.1:3000</code> or <code>http://localhost:3000</code></li>
</ul>

## Requirement 
<ul>
  <li>Install Docker</li>
  <li>Install Kubernetes</li>
  <li>Expose port number 3000</li>
</ul>

## Docker Integration 
<ul>
  <li>First rename the .env.example to .env</li>
  <li>Use Docker to build the image</li>
  <li>Command: docker build -t meals-app .</li>
  <li>Use this command to run the image</li>
  <li>Command: docker run -d -p 3000:80 meals-app</li>
</ul>

## Kubernetes Integration 
<ul>
  <li>Go to k8s folder/directory</li>
  <li>Use this command to apply the k8s files present inside folder/directory</li>
  <li>Command: kubectl apply -f .</li>
</ul>
