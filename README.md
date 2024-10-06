# Agenda-based Search London Tube

## :loudspeaker: Disclaimer

This repository is part of the deliverables for my MSc AI module. Unauthorized reproduction of this project, including for plagiarism or any form of academic dishonesty, is strictly prohibited. The content is intended to showcase my skills and may be used for reference purposes only with proper attribution.

## :scroll: Description
This repository involves the implementation of four algorithms for an AI route finder using agenda-based search mechanism.

The four algorithms used are:
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)
- Best-First Search (BFS) (Heuristic Search)

An in-depth comparison of the algorithms is performed based on the average time taken and number of nodes explorations.

## :bar_chart: Results

### Table 1: Direct Order of Explored Nodes
<table>
    <tr>
        <th>Route: Canada Water to Stratford</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>246</td>
        <td>38</td>
        <td>201</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>15</td>
        <td>15</td>
        <td>14</td>
    </tr>
    <tr>
        <th>Route: New Cross Gate to Stepney Green</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>24</td>
        <td>26</td>
        <td>68</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>25</td>
        <td>14</td>
        <td>14</td>
    </tr>
    <tr>
        <th>Route: Ealing Broadway to South Kensington</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>45</td>
        <td>49</td>
        <td>77</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>58</td>
        <td>20</td>
        <td>32</td>
    </tr>
    <tr>
        <th>Route: Baker Street to Wembley Park</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>9</td>
        <td>15</td>
        <td>155</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>13</td>
        <td>13</td>
        <td>54</td>
    </tr>
</table>

### Table 2: Reverse Order of Explored Nodes

<table>
    <tr>
        <th>Route: Canada Water to Stratford</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>224</td>
        <td>27</td>
        <td>201</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>20</td>
        <td>15</td>
        <td>14</td>
    </tr>
    <tr>
        <th>Route: New Cross Gate to Stepney Green</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>267</td>
        <td>40</td>
        <td>62</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>14</td>
        <td>14</td>
        <td>14</td>
    </tr>
    <tr>
        <th>Route: Ealing Broadway to South Kensington</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>69</td>
        <td>48</td>
        <td>108</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>57</td>
        <td>20</td>
        <td>33</td>
    </tr>
    <tr>
        <th>Route: Baker Street to Wembley Park</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>228</td>
        <td>11</td>
        <td>158</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>63</td>
        <td>13</td>
        <td>54</td>
    </tr>
</table>

## Table 3: Extending the Cost Function

UCS cost function is extended to include the time to change lines at one station (e.g., 2 minutes).

<table>
    <tr>
        <th>Route: Euston to Victoria</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>  
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>136</td>
        <td>40</td>
        <td>40</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>15</td>
        <td>7</td>
        <td>7</td>
    </tr>
    <tr>
        <th>With Extending</th>
        <th>DFS</th>
        <th>BFS</th>
        <th>UCS</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>136</td>
        <td>40</td>
        <td>98</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>29</td>
        <td>13</td>
        <td>13</td>
    </tr>
</table>

## Table 4: Heuristic Search

<table>
    <tr>
        <th>Route: Euston to Victoria</th>
        <th>Best-First Search</th>
        <th>Uniform Cost Search</th>
    </tr>
    <tr>
        <td>No. of Explorations</td>
        <td>20</td>
        <td>30</td>
    </tr>
    <tr>
        <td> Cost in Average Time</td>
        <td>7</td>
        <td>7</td>
    </tr>
</table>
