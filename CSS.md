@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');

:root {
  --accent-color: #4928FF;
  --base-color: #000000;
  --light-color: #EAEAEA;
  --background-color: #E3E3E3;
}

body {
  font-family: 'Inter', sans-serif;
  background-color: var(--background-color);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.container {
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  width: 400px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 16px;
  border-bottom: 1px solid var(--light-color);
}

.title {
  font-size: 64px;
  font-weight: 700;
  color: var(--base-color);
}

.close-btn {
  font-size: 24px;
  font-weight: 700;
  color: var(--base-color);
  cursor: pointer;
}

.content {
  padding: 24px;
}

.percentage {
  font-size: 64px;
  font-weight: 700;
  color: var(--accent-color);
  text-align: center;
}

.chart {
  display: flex;
  justify-content: center;
  margin-top: 24px;
}

.chart-item {
  width: 10px;
  height: 60px;
  background-color: var(--accent-color);
  margin: 0 4px;
}
