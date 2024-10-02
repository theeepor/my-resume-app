<template>
  <div id="app">
    <h1>Lee</h1>
    
    <section>
      <h2>Profile</h2>
      <p>Im Batman.</p>
    </section>
    
    <section>
      <h2>Education</h2>
      <ul>
        <li>
          <strong>Degree</strong> - Web Development (3rd Year)
        </li>
        <!-- Add more education entries as needed -->
      </ul>
    </section>
    
    <section>
      <h2>Skills</h2>
      <ul>
        <li>Skill 1: java</li>
        <li>Skill 2: HTML</li>
        <li>Skill 3: Python</li>
        <li>Skill 4: Javascript</li>
        <!-- Add more skills as needed -->
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  color: #333;
  line-height: 1.6;
  margin: 0;
  padding: 20px;
  background-color: #f9f9f9;
}

h1 {
  font-size: 36px;
  font-weight: bold;
  text-align: center;
  color: #4a4a4a;
  margin-bottom: 20px;
}

h2 {
  font-size: 28px;
  color: #3a3a3a;
  border-bottom: 2px solid #3a3a3a;
  padding-bottom: 5px;
  margin-bottom: 10px;
}

section {
  margin-bottom: 30px;
  background-color: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

p, li {
  font-size: 18px;
  margin-bottom: 10px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  padding-left: 20px;
  position: relative;
}

li:before {
  content: '•';
  position: absolute;
  left: 0;
  color: #00aaff;
  font-size: 20px;
}

strong {
  font-weight: bold;
  color: #333;
}

a {
  color: #00aaff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  #app {
    padding: 10px;
  }

  h1 {
    font-size: 30px;
  }

  h2 {
    font-size: 24px;
  }

  p, li {
    font-size: 16px;
  }
}

</style>
