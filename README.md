<h1 align="center">Hi 👋, I'm Sean Kim</h1>
<h3 align="center">Software Architect and Engineer</h3>


📫 Email: **snk.bus@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/sean-kim-222576120/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sean-kim-222576120/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<div align="left">
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/python.png" alt="Python" title="Python"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postgresql.png" alt="PostgreSQL" title="PostgreSQL"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/mysql.png" alt="MySQL" title="MySQL"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/mssql.png" alt="MSSQL" title="MSSQL"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/microsoft_azure.png" alt="Microsoft Azure" title="Microsoft Azure"/></code>
 	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/graphql.png" alt="GraphQL" title="GraphQL"/></code>
</div>

<h2><b></b>Overview:</b></h2>
<p>
 I'm product-driven, leveraging IT and business to develop creative solutions that optimize workflows and enhance user experience. My approach is centered around building a solution that keeps it simple while truly hammering home the impact it has on work efficiency.
</p>
<p>
Looking for a hybrid gig around Sunnvaly, CA, one that will kick start my coding career and challenge my abilities.
</p>


<h2><b>Projects:</b></h2>
	<ol>
		<li> <h3> <b>Inventory Auditor </b> </h3>  
			<table>
				<tr>
					<th>Description</th>
					<td> 
						<p><b>Brief:</b> Runs a quick check to identify discrepancies between system and physical count for inventory assets. Used to speed up the pre-audit process. 
						</p>
						<p>
						<b>How it works:</b> This application compares two datasets that are first exported and placed into designated folders. The code reads both sheets, formats them to ensure consistency, and performs a comparison using a table join. Any discrepancies are flagged, indicating whether an asset is missing physically or systematically. A report is then generated, and while the app runs, it displays a visual summary, concluding with a PASS/FAIL status based on the match
						</p>
						<p>
						<b>Motive:</b> I created this application not only to save time but also to reduce the mental strain of performing the repetitive task of manually reviewing datasets. 
						</p>
					</td>
				</tr>
				<tr>
					<th>Tech Stack</th>
					<td>
						<ul>
						 <li><b>Python:</b> pandas | SQLAlchemy | psycopg2 | csv | rich | re</li>
						 <li><b>SQL:</b> PostgreSQL</li>
						 <li><b>Other:</b> Google Sheets</li>
						</ul>  
					</td>
				</tr>
				<tr>
					<th>Code</th>
					<td>
						Link to [<a href="https://github.com/snynkm/deployment/tree/main/deployment/inventory_control">Inventory Auditor Repository </a>] 💻
					</td>
				</tr>
				<tr>
					<th>Images</th>
					<td> 
						<table style="width:100; height:auto" border="0p">
							<tr>
								<td>
								<img style="width:auto; height:500px" src="https://github.com/user-attachments/assets/d4145384-ffe6-4f61-9491-90a84609b2e3" alt="Post Process Report" >
								<img style="width:auto; height:500px" src="https://github.com/user-attachments/assets/6b33a7a4-36b0-490d-a0e2-edd90ac39e27" alt="Storage Room Screenshot" >
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>  
		</li>

  <li> <h3> <b>VM Quantity Manager</b> </h3>  
	<table>
		<tr>
			<th>Description</th>
			<td> 
				<p><b>Brief:</b> Tracks and manages the systematic quantities of VM accessories. 
				</p>
				<p>
				<b>How it works:</b> I set up Tableau to send me an automated email every morning, containing a PDF with a breakdown of current stock levels. The code filters for this email in Outlook, downloads the PDF to a specific folder, extracts the relevant data, and loads into a dataframe. It then pulls existing data from a database, compares the values, and updates the database accordingly based on the applications selected options. Lastly, the updated dataset is display and visualization highlits the current stock percents for each vending machine item.
				</p>
				<p>
				<b>Motive: </b>The motivation behind this project is to optimize daily VM maintenance by identifying when refills are necessary. This system allows me to focus on higher-priority tasks, while ensuring that stock levels remain sufficient for users.
				</p>
			</td>
		</tr>
		<tr>
			<th>Tech Stack</th>
			<td>
			  <ul>
			    <li><b>Python:</b> pandas | PymuPDF | SQLAlchemy | win32com.client | psycopg2 | csv | rich</li>
			    <li><b>SQL:</b> PostgreSQL</li>
			    <li><b>Data Visualization:</b> Tableau</li>
			    <li><b>Other:</b> Outlook</li>
			  </ul>  
			</td>
		</tr>
		<tr>
			<th>Code</th>
			<td>
				Link to [<a href="https://github.com/snynkm/deployment/tree/main/deployment/vending_machine">VM Quantity Manager Repository </a>] 💻
			</td>
		</tr>
		<tr>
		<th>Images</th>
		<td> 
			<table style="width:100; height:auto" border="0p">
			<tr>
				<td>
				<img style="width:auto; height:500px; object-fit:contain" src="https://github.com/user-attachments/assets/86781523-6082-4607-8c07-288db4972ded" alt="Post Process Report" >
				<img style="width:auto; height:500px; object-fit:contain" src="https://github.com/user-attachments/assets/fb286224-8f4f-4135-aa88-d62bf269f4f8" alt="Vending Machine Screenshot" >
				</td>
			</tr>
			<tr>
				<td>
				<img style="width:auto; height:450px" src="https://github.com/user-attachments/assets/764cd58e-4bd3-415d-a85c-02795b5a9185" alt="Dataframe" >
				</td>
			</tr>
			<tr>
				<td>
				<img style="width:auto; height:500px" src="https://github.com/user-attachments/assets/af99c08d-d950-41e4-b5d6-978729176ae9" alt="Entity Relationship Diagram" >
				</td>
			</tr>
			</table>
		</td>
		</tr>
	</table>  
  </li>
  
<li> <h3> <b>Mock E-Commerce Website</b> </h3>  
  <table>
    <tr>
      <th>Title</th>
      <td> 🔥🍕 Vennato's Pizza 🍕🔥</td>
    </tr>
    <tr>
      <th>Live Website Url:</th>
      <td>[Disabled] [Visit Vennato's Pizza ]</td>
    </tr>
    <tr>
      <th>Description</th>
      <td>
	<p><b>Brief: </b>Provides a platform where users can view a menu catalog and submit orders.
      </p>
      <p>
	      <b>Motive: </b>I made this application back when I was first learning C#. I've decided to focus more on Python going forward, but I still wanted to showcase this project.It is the first full-stack web application I've built. It was a very challenging project, but I had lots of fun with it. 
      </p>
      </td>
    </tr>
    <tr>
      <th>Code</th>
      <td> Link to [<a href="https://github.com/snynkm/VP-Blazor-Azure">Vennato's Pizza Repository</a>] 💻 </td>
    </tr>
    <tr>
      <th>Tech Stack</th>
      <td>
        <ul>
          <li><b>Front-End:</b> HTML | CSS | MudBlazor</li>
          <li><b>Back-End (Server-Side Web App Dev Tools):</b> Blazor Server | Dapper ORM</li>
          <li><b>Back-End (Database):</b> Azure SQL Database | MS SQL Server</li>
          <li><b>IDEs:</b> Visual Studio | SSMS </li>
          <li><b>Version Control:</b> Git</li>
          <li><b>Hosting Service</b> GitHub</li>
          <li><b>PaaS:</b> Azure Web Apps & App Service</li>
          <li><b>PM:</b> Trello</li>
        </ul>  
      </td>
    </tr>
  </table>  
</li>

</ol>
