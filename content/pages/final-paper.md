---
content_type: page
description: This section includes guidelines for writing the final paper for the
  course, LaTeX guidelines, a list of possible paper topics, and sample final papers
  written by students in the class.
learning_resource_types: []
ocw_type: CourseSection
title: Final Paper
uid: 6b9bfa3d-ceed-67e5-a93d-cd0254b0e116
---

{{% resource_link 6b9bfa3d-ceed-67e5-a93d-cd0254b0e116 "Guidelines" "#1" %}}

{{% resource_link 6b9bfa3d-ceed-67e5-a93d-cd0254b0e116 "Topic Selection" "#2" %}}

{{% resource_link 6b9bfa3d-ceed-67e5-a93d-cd0254b0e116 "Sample Student Final Papers" "#3" %}}

{{< anchor "1" >}}{{< /anchor >}}Guidelines
-------------------------------------------

The final paper is an approximately 10 page exposition on a topic in algebraic topology not covered in our seminar. The paper must be written in {{% resource_link "d7810449-91e4-4787-a762-201df4d2fe0f" "LaTeX" %}} (or some other flavor of {{% resource_link "daca64d8-b38c-4ee0-9001-9f0a82312f49" "TeX" %}}).

Here are some {{% resource_link f375162f-a875-71fd-6b8a-9a281944cf8f "LaTeX guidelines (PDF)" %}}—and the {{% resource_link e8009715-bf17-ba32-251f-acf8ce619c9c "LaTeX guidelines .tex source" %}}—that gives some examples of how to do things like matrices and commutative diagrams, and also discusses some things that you should and should not do in latex (repeated in abridged form below).

*   Do not begin sentences (or phrases) with math. Do not put math next to math.
*   Multi-letter operators and functions, like sin, should not be italicized.
*   Use the correct size parentheses.
*   When multiple formulas are put into a single displaymath (LaTeX math mode), put space between them.
*   The default margins are much too large; adjust them.

I've put together a list of mistakes that were common in the drafts of your final papers. Every draft that I read contained at least one of these mistakes, so I recommend that you all look through this and apply what it says to your writing. These remarks are elaborated upon in the file {{% resource_link 343d96d1-35a7-2300-f69c-9338178d46bd "Comments on Final Paper Drafts (PDF)" %}}

{{< anchor "2" >}}{{< /anchor >}}Topic Selection
------------------------------------------------

You must select the topic for your paper by session 15. I'd prefer that no two of you do the same topic. Below is a list of possible ideas for topics. You're free to choose something not on this list, but run it by me first.

### Concrete Topics

*   **Hopf fibrations**. The Hopf fibrations are three specific maps of spheres defined using projective spaces over the complex numbers, quaternions and octonions. They were the first non-trivial elements of higher homotopy groups of spheres to be discovered.
*   **Lens spaces**. The lens spaces are an explicit family of 3-dimensional manifolds indexed by pairs of integers. They provided the first example of a pair of compact manifolds which are homotopy equivalent but not homeomorphic.
*   **PSL{{< sub "2" >}}(Z) as a free product**. Using some algebraic topology, one can give a nice proof that PSL{{< sub "2" >}}(Z) (roughly the group 2×2 integer matrices) is the free product of a cyclic group of order 2 and a cyclic group of order 3.

### Homology Theories

*   **Borel–Moore homology and cohomology with supports**. These variants of homology and cohomology are useful when dealing with non-compact spaces. They allow one to extend Poincaré duality to the setting of non-compact manifolds.
*   **de Rham cohomology**. This is a cohomology theory for smooth manifolds defined in terms of differential forms. The main theorem, the de Rham isomorphism theorem, states that de Rham cohomology is isomorphic to singular cohomology (with real coefficients). This is remarkable since the definition uses the smooth structure on the manifold but the final product is only dependent on the topology. p-adic analogues of this result have been very important in number theory in recent years.
*   **Sheaf theory**. Sheaves are to topological spaces what modules are to rings. There is a notion of cohomology for a sheaf on a topological space; the cohomology of the so-called "constant sheaf" gives the singular cohomology of the space. Sheaf theory is indispensable in modern algebraic geometry.
*   **K-theory**. Given a space X, a group K{{< sub "0" >}}(X) is constructed using complex vector bundles on X. Groups K{{< sub "n" >}}(X) can be constructed in various manners. The K-groups are not isomorphic to the singular cohomology groups. K-theory forms what is called an "extraordinary cohomology theory." The most important result is Bott periodicity, which states that the K-groups are periodic with period 2.

### Categorical Methods

*   **Simplicial sets**. The theory of simplicial sets offers a model of homotopy theory without using topological spaces. Instead, it relies on certain diagrams of sets. Homology can be described elegantly in this theory; in fact, it essentially amounts to taking the free abelian group on the simplicial set.
*   **The fundamental groupoid**. The fundamental group of a topological space depends on the choice of a basepoint, which can be inconvenient. The fundamental groupoid is something like the fundamental group, but does not depend on any choice. However, it is a category instead of a group. This can be extended to higher homotopy groups through the use of higher categories.
*   **The derived category**. The Kunneth formula states that H•(X × Y)=H•(X) ⊗ H•(Y), up to some error terms involving Tor's. Similarly, the universal coefficient theorem states that H•(X; R)=H•(X; Z) ⊗ R, again up to some error terms involving Tor's. Derived categories provide a way to eliminate these error terms, which is very desirable. The basic idea of derived categories is to systematically work with the complexes that compute homology, rather than homology itself. Derived categories are very important in a wide variety of subjects these days.

### Classifying Spaces

*   **Eilenberg–MacLane spaces**. Let G be a group and let n≥1 be an integer; if n>1 then assume that G is commutative. One can then show that there is a unique homotopy type X with π{{< sub "n" >}}(X)=G and π{{< sub "k" >}}(X)=1 for k≠n. This homotopy type is usually denoted K(G, n) and called an Eilenberg–MacLane space. One reason that these spaces are interesting is that they represent cohomology: giving an element of H{{< sup "n" >}}(X; G) is the same as giving a homotopy class of maps X → K(G, n).
*   **Group cohomology**. Let G be a group. As stated above, there is an associated homotopy type K(G, 1). The (co)homology of K(G, 1) is an invariant of the group G, called group (co)homology. One can give a purely algebraic construction of group (co)homology, however, the topological perspective is often useful as well.
*   **The classifying space for vector bundles**. Let n≥1 be an integer. There is then a space B with the following property: homotopy classes of maps from an arbitrary space X into B are canonically in bijection with complex vector bundles of rank n on X. The space B is infinite dimensional, but can be described explicitly as a Grassmannian. Using classifying spaces, one can associate cohomology classes to vector bundles; this is the theory of characteristic classes.

### Higher Homotopy Groups

*   **The long exact sequence**. A fibration is the analogue in the world of homotopy theory to the concept of a short exact sequence. Given a fibration F → X → B, there is a long exact sequence relating the homotopy groups of F, X and B. This can be used to calculate some higher homotopy groups.
*   **The Freudenthal suspension theorem**. This result states that, in certain cases, homotopy groups of suspensions of a space stabilize; precisely, π{{< sub "n+k" >}}(S{{< sup "k" >}}X) is independent of k when k is large. This leads to the concept stable homotopy groups, and a whole stable homotopy theory.
*   **The Hurewicz homomorphism**. There is a natural map from homotopy to singular homology, called the Hurewicz homomorphism. Hurewicz showed that for a simply connected space, the first non-zero homotopy and homology groups are isomorphic via this map.

### Other Topics

*   **Spectral sequences**. As mentioned above, associated to a fibration of spaces is a long exact sequence of homotopy groups. The behavior of homology in a fibration is not as simple—it is described by an algebraic construct called a spectral sequence. One can use spectral sequences to compute the homology of certain spaces, such as Lie groups and some loop spaces.
*   **Steenrod squares**. Steenrod constructed a natural map H{{< sup "n" >}}(X; F{{< sub "2" >}})→ H{{< sup "n+i" >}}(X F{{< sub "2" >}}) for each i, which is now called the Steenrod square Sq{{< sup "i" >}}. This gives the cohomology of a space with F{{< sub "2" >}} coefficients extra structure, and allows one to distinguish spaces using cohomology that one could not before.
*   **Morse theory**. This theory gives a way to decompose a manifold using critical points of functions on it. John Milnor has a nice book on the subject.
*   **The Gauss–Bonnet theorem**. Given a surface in Euclidean space (or, more abstractly, a Riemannian manifold of dimension 2), one can speak of the curvature of the surface at a point. The Gauss–Bonnet theorem states that the total curvature (the integral over the surface of the curvature at each point) is equal to the Euler characteristic of the surface. Like the de Rham theorem mentioned above, this is remarkable since it shows that the total curvature of a surface is a topological invariant, even though this is not apparent in its definition.

{{< anchor "3" >}}{{< /anchor >}}Sample Student Final Papers
------------------------------------------------------------

Three of the students in the class have provided their final papers for publication on OCW and they are presented here with their permission.

{{% resource_link ddb67681-e7f7-5f31-931a-73d2fd1ecb41 "Introduction to Orbifolds (PDF)" %}}

{{% resource_link 630fecdd-09a7-90c3-19d5-75f60287dfbc "An Introduction to Simplicial Sets (PDF)" %}}

{{% resource_link d647c89d-91c0-9829-722b-eda80a87705a "The Hurewicz Theorem (PDF)" %}}