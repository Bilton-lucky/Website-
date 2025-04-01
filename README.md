/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header */
header {
    background: #fff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    padding: 15px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: 700;
    color: #6200ea;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 25px;
}

.nav-links a:hover {
    color: #6200ea;
}

.btn {
    padding: 8px 16px;
    border-radius: 4px;
    font-weight: 600;
}

.btn-login {
    border: 1px solid #6200ea;
    color: #6200ea;
}

.btn-signup {
    background: #6200ea;
    color: white;
}

/* Categories Section */
.categories {
    padding: 50px 0;
}

h2 {
    margin-bottom: 30px;
    font-size: 28px;
    color: #333;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.category-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.3s;
}

.category-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.category-image {
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 48px;
}

.category-content {
    padding: 20px;
}

.category-content h3 {
    margin-bottom: 10px;
}

.category-content a {
    color: #6200ea;
    font-weight: 600;
    display: inline-block;
    margin-top: 10px;
}

/* Featured Section */
.featured {
    padding: 50px 0;
    background: #f9f9f9;
}

.featured-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 30px;
}

.featured-item {
    display: flex;
    gap: 20px;
    margin-bottom: 30px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

.featured-image {
    min-width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 40px;
    border-radius: 8px;
}

.featured-text h3 {
    margin-bottom: 10px;
}

.featured-text a {
    color: #6200ea;
    font-weight: 600;
}

aside {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

aside h3 {
    margin-bottom: 15px;
}

aside ul {
    list-style: none;
}

aside li {
    margin-bottom: 10px;
}

aside a:hover {
    color: #6200ea;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    padding: 50px 0 20px;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 30px;
    margin-bottom: 30px;
}

.footer-column h3 {
    margin-bottom: 20px;
    font-size: 18px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 10px;
}

.footer-column a:hover {
    color: #bb86fc;
}

.copyright {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid #555;
}

/* Responsive */
@media (max-width: 768px) {
    .featured-grid {
        grid-template-columns: 1fr;
    }

    .featured-item {
        flex-direction: column;
    }

    .featured-image {
        width: 100%;
    }
}/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header */
header {
    background: #fff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    padding: 15px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: 700;
    color: #6200ea;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 25px;
}

.nav-links a:hover {
    color: #6200ea;
}

.btn {
    padding: 8px 16px;
    border-radius: 4px;
    font-weight: 600;
}

.btn-login {
    border: 1px solid #6200ea;
    color: #6200ea;
}

.btn-signup {
    background: #6200ea;
    color: white;
}

/* Categories Section */
.categories {
    padding: 50px 0;
}

h2 {
    margin-bottom: 30px;
    font-size: 28px;
    color: #333;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.category-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.3s;
}

.category-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.category-image {
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 48px;
}

.category-content {
    padding: 20px;
}

.category-content h3 {
    margin-bottom: 10px;
}

.category-content a {
    color: #6200ea;
    font-weight: 600;
    display: inline-block;
    margin-top: 10px;
}

/* Featured Section */
.featured {
    padding: 50px 0;
    background: #f9f9f9;
}

.featured-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 30px;
}

.featured-item {
    display: flex;
    gap: 20px;
    margin-bottom: 30px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

.featured-image {
    min-width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 40px;
    border-radius: 8px;
}

.featured-text h3 {
    margin-bottom: 10px;
}

.featured-text a {
    color: #6200ea;
    font-weight: 600;
}

aside {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

aside h3 {
    margin-bottom: 15px;
}

aside ul {
    list-style: none;
}

aside li {
    margin-bottom: 10px;
}

aside a:hover {
    color: #6200ea;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    padding: 50px 0 20px;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 30px;
    margin-bottom: 30px;
}

.footer-column h3 {
    margin-bottom: 20px;
    font-size: 18px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 10px;
}

.footer-column a:hover {
    color: #bb86fc;
}

.copyright {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid #555;
}

/* Responsive */
@media (max-width: 768px) {
    .featured-grid {
        grid-template-columns: 1fr;
    }

    .featured-item {
        flex-direction: column;
    }

    .featured-image {
        width: 100%;
    }
}/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header */
header {
    background: #fff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    padding: 15px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: 700;
    color: #6200ea;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 25px;
}

.nav-links a:hover {
    color: #6200ea;
}

.btn {
    padding: 8px 16px;
    border-radius: 4px;
    font-weight: 600;
}

.btn-login {
    border: 1px solid #6200ea;
    color: #6200ea;
}

.btn-signup {
    background: #6200ea;
    color: white;
}

/* Categories Section */
.categories {
    padding: 50px 0;
}

h2 {
    margin-bottom: 30px;
    font-size: 28px;
    color: #333;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.category-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.3s;
}

.category-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.category-image {
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 48px;
}

.category-content {
    padding: 20px;
}

.category-content h3 {
    margin-bottom: 10px;
}

.category-content a {
    color: #6200ea;
    font-weight: 600;
    display: inline-block;
    margin-top: 10px;
}

/* Featured Section */
.featured {
    padding: 50px 0;
    background: #f9f9f9;
}

.featured-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 30px;
}

.featured-item {
    display: flex;
    gap: 20px;
    margin-bottom: 30px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

.featured-image {
    min-width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 40px;
    border-radius: 8px;
}

.featured-text h3 {
    margin-bottom: 10px;
}

.featured-text a {
    color: #6200ea;
    font-weight: 600;
}

aside {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

aside h3 {
    margin-bottom: 15px;
}

aside ul {
    list-style: none;
}

aside li {
    margin-bottom: 10px;
}

aside a:hover {
    color: #6200ea;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    padding: 50px 0 20px;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 30px;
    margin-bottom: 30px;
}

.footer-column h3 {
    margin-bottom: 20px;
    font-size: 18px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 10px;
}

.footer-column a:hover {
    color: #bb86fc;
}

.copyright {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid #555;
}

/* Responsive */
@media (max-width: 768px) {
    .featured-grid {
        grid-template-columns: 1fr;
    }

    .featured-item {
        flex-direction: column;
    }

    .featured-image {
        width: 100%;
    }
}
