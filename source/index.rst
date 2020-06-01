.. Human-Robot Interactive Learning documentation master file, created by
   sphinx-quickstart on Tue Mar  6 22:44:00 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

TUNI Human Robot Teams documentation
====================================

Installation instructions
-------------------------

Install all necessary components.

* **Instructions**:
  :doc:`Dependencies </install/dependencies>` |
  :doc:`Setup </install/setup>`


.. toctree::
   :maxdepth: 2
   :caption: Installation:

   /install/dependencies
   /install/setup


Get Started
-----------

* **Overview of core features**:
  :doc:`Knowledge base </start/data>`
  :doc:`Planner </start/planner>`
  :doc:`Robotic platform </start/robot>`

  .. toctree::
     :maxdepth: 2
     :caption: Get Started:

     /start/data
     /start/planner
     /start/robot

Tutorials
---------

* **Assembly task**:
  :doc:`Cranfield assembly </tuto/cranfield>`

* **Handover**:
  :doc:`From robot to human </tuto/handover-robot-human>`
  :doc:`From human to robot </tuto/handover-human-robot>`

* **Packing task**:
  :doc:`Clean tabletop </tuto/packing>`

  .. toctree::
     :maxdepth: 2
     :caption: Get Started:

     /start/data
     /start/planner
     /start/robot

Representation
--------------

   Description of Hierarchical Task Network and its application to knowledge based robotics.

   * **Industrial robotics ontology**:
     :doc:`Concepts </representation/concepts>`
     :doc:`Properties </representation/properties>`

   * **Hierarchical Task Network (HTN)**:
     :doc:`Basics </representation/basics>`
     :doc:`Examples </representation/example>`

   * **Semantic Planning**:
     :doc:`Planning ontology </representation/ontology>`
     :doc:`Establish a plan </representation/make-plan>`


   .. toctree::
      :maxdepth: 2
      :hidden:
      :caption: Knowledge representation

      /representation/basics
      /representation/example

      /representation/ontology
      /representation/make-plan


Interaction
-----------

   Description of Hierarchical Task Network and its application to knowledge based robotics.

   * **Natural Language interface**:
     :doc:`Planning ontology </representation/ontology>`
     :doc:`Establish a plan </representation/make-plan>`

  * **Graphical user interface**:
      :doc:`Qt </representation/ontology>`


Machine Teaching
----------------

   * **Object semantic annotations**:
     :doc:`FreeCad </teaching/freecad>`
     :doc:`Semantic Annotation workbench </teaching/sem-annotation>`

   * **Skill teaching**:
     :doc:`Qt Interface </teaching/qt>`
     :doc:`Examples </teaching/example>`

  .. toctree::
    :maxdepth: 2
    :hidden:
    :caption: Machine Teaching

    /teaching/freecad
    /teaching/sem-annotation

    /teaching/qt
    /teaching/example

Troubleshooting
---------------

* **Planner**:
  :doc:`Jupyter-notebook </troubleshooting/jupyter>`


* ****:
  :doc:`Docker </troubleshooting/docker>`


  .. toctree::
    :maxdepth: 2
    :hidden:
    :caption: Troubleshooting

    /troubleshooting/jupyter
    /troubleshooting/docker
