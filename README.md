# tensornetwork-project-3--multi-exciton-generation-in-molecular-semiconductors-via-singlet-fission-so
**TO GET THIS SOLUTION VISIT:** [TensorNetwork Project 3- Multi-exciton generation in molecular semiconductors via singlet fission So](https://www.ankitcodinghub.com/product/tensornetwork-multi-exciton-generation-in-molecular-semiconductors-via-singlet-fission-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126140&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;TensorNetwork Project 3- Multi-exciton generation in molecular semiconductors via singlet fission Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In organic solar cells (OSCs), incident photons are absorbed by a photoactive material to form excited electronic states, known as excitons. Excitons are then transported in the material until they reach an electron acceptor, where they undergo charge separation, producing a photocurrent. However, the short nanosecond lifetime of excitons limits the efficiency of OSCs.

Singlet fission is an electronic processes that is now being explored as a way to improve the efficiency of organic solar cells. In singlet fission, a photo-generated exciton with spin 0 (known as singlet) splits into two excitons with spin 1 (known as triplets) in a energy-conserving and spinconserving transition. This process can improve OSCs efficiency by producing two excitons per absorbed photon, and by increasing the probability for the excitons to reach an electron acceptor, since triplets have a microsecond lifetime.

In this project we will implement a numerical model to study singlet fission in extended solids, which remains a challenge in the field. In particular, we will consider a 1D lattice of molecules and using tensor networks (TNs) to solve a many-body model of singlet fission. After comparing the TNs results with known solutions, we will scale up the model to study how singlet fission scales with the number $N$ of molecules. Finally, we will study the effect of disorder and of the vibrational modes of the molecular lattice.

drawing

Tasks

Following the notes on singlet fission, use qtealeaves to implement the singlet fission Hamiltonian for 1D rings with $N$ sites (nearestneighbour couplings and periodic boundary conditions). Ignore the vibrational modes so that each site represents an exciton site.

Study the unitary dynamics of an initial singlet exciton state. Consider the parameters of the resonant triplet-pair solution with singlet exciton energy $arepsilon_S = 1$ (see notes) and initialise the system in the ground state of the singlet exciton Hamiltonian with $n_0 = 1$ singlet in the medium. Propagate this initial state via a quench monitoring the total number of singlets and triplets, and compare the results with the solution provided in the jupyter notebook for $N = 4$.

How does the solution change with the bond dimension (max_bond_dimension)? Does the dynamics change with the number $N$ of sites?

Implement the function to evaluate singlet fission efficiency over a time interval (see notes) and study the efficiency of singlet fission (i.e., how likely 2$n$ triplets are formed per $n$ initial singlet excitons) as a function of the initial number of singlet excitons $n_0in(1,N)$. How does the problem’s computational complexity change with $n_0$?

Generalise the model by allowing disorder (see code snippet for help) both in the local terms and in the two-body interactions. Study the dynamics of the system with disorder in the triplet hopping coupling $J_T$ and in the triplet-triplet interaction $chi$, by averaging over multiple trajectories, each with a different realisation of disorder. Only consider one initial singlet in the medium ($n_0=1$). Does disorder improve or worsen singlet fission efficiency?

Extend the model by adding one vibrational mode (phonon) per site (see notes). Embed the excitons and the phonon (which can be modelled as a boson) within the same site (see code snippet for help) and limit the size of the phonon to $n_{max} = 3$

(fock_space_nmax = 3). Assume that the phonons relax via the local Lindblad operators $a$, with relaxation rate $gamma_- = 0.1 arepsilon_S$. Couple the phonon to the excitons only via singlet-phonon interactions with coupling strength $g_S$. Study the dynamics of the exciton-phonon system as a function of $g_S$ for $N=4$ ignoring disorder. Use the open system mode for quantum trajectories with jumps (oqs_mode = 1).
