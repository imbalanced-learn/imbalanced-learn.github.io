:orphan:



.. _sphx_glr_auto_examples:

.. _general_examples:

Examples
--------

General-purpose and introductory examples for the `imbalanced-learn` toolbox.


.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_api:

.. _api_usage:

Examples showing API imbalanced-learn usage
-------------------------------------------

Examples that show some details regarding the API of imbalanced-learn.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the different usage of the parameter sampling_strategy for the different fam...">

.. only:: html

 .. figure:: /auto_examples/api/images/thumb/sphx_glr_plot_sampling_strategy_usage_thumb.png
     :alt: How to use ``sampling_strategy`` in imbalanced-learn

     :ref:`sphx_glr_auto_examples_api_plot_sampling_strategy_usage.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/api/plot_sampling_strategy_usage
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_applications:

.. _realword_examples:

Examples based on real world datasets
-------------------------------------

Examples which use real-word dataset.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Some balancing methods allow for balancing dataset with multiples classes. We provide an exampl...">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_plot_multi_class_under_sampling_thumb.png
     :alt: Multiclass classification with under-sampling

     :ref:`sphx_glr_auto_examples_applications_plot_multi_class_under_sampling.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/plot_multi_class_under_sampling

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows how to balance the text data before to train a classifier.">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_plot_topic_classication_thumb.png
     :alt: Example of topic classification in text documents

     :ref:`sphx_glr_auto_examples_applications_plot_topic_classication.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/plot_topic_classication

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the use of a custom sampler to implement an outlier rejections estimat...">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_plot_outlier_rejections_thumb.png
     :alt: Customized sampler to implement an outlier rejections estimator

     :ref:`sphx_glr_auto_examples_applications_plot_outlier_rejections.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/plot_outlier_rejections

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this face recognition example two faces are used from the LFW (Faces in the Wild) dataset. S...">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_plot_over_sampling_benchmark_lfw_thumb.png
     :alt: Benchmark over-sampling methods in a face recognition task

     :ref:`sphx_glr_auto_examples_applications_plot_over_sampling_benchmark_lfw.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/plot_over_sampling_benchmark_lfw

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example compares two strategies to train a neural-network on the Porto Seguro Kaggle data ...">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_porto_seguro_keras_under_sampling_thumb.png
     :alt: Porto Seguro: balancing samples in mini-batches with Keras

     :ref:`sphx_glr_auto_examples_applications_porto_seguro_keras_under_sampling.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/porto_seguro_keras_under_sampling

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the problem induced by learning on datasets having imbalanced classes....">

.. only:: html

 .. figure:: /auto_examples/applications/images/thumb/sphx_glr_plot_impact_imbalanced_classes_thumb.png
     :alt: Fitting model on imbalanced datasets and how to fight bias

     :ref:`sphx_glr_auto_examples_applications_plot_impact_imbalanced_classes.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/applications/plot_impact_imbalanced_classes
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_combine:

.. _combine_examples:

Examples using combine class methods
====================================

Combine methods mixed over- and under-sampling methods. Generally SMOTE is used for over-sampling while some cleaning methods (i.e., ENN and Tomek links) are used to under-sample.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the effect of applying an under-sampling algorithms after SMOTE over-samplin...">

.. only:: html

 .. figure:: /auto_examples/combine/images/thumb/sphx_glr_plot_comparison_combine_thumb.png
     :alt: Compare sampler combining over- and under-sampling

     :ref:`sphx_glr_auto_examples_combine_plot_comparison_combine.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/combine/plot_comparison_combine
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_datasets:

.. _dataset_examples:

Dataset examples
-----------------------

Examples concerning the :mod:`imblearn.datasets` module.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="An illustration of the make_imbalance function to create an imbalanced dataset from a balanced ...">

.. only:: html

 .. figure:: /auto_examples/datasets/images/thumb/sphx_glr_plot_make_imbalance_thumb.png
     :alt: Create an imbalanced dataset

     :ref:`sphx_glr_auto_examples_datasets_plot_make_imbalance.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/datasets/plot_make_imbalance
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_ensemble:

.. _ensemble_examples:

Example using ensemble class methods
====================================

Under-sampling methods implies that samples of the majority class are lost during the balancing procedure.
Ensemble methods offer an alternative to use most of the samples.
In fact, an ensemble of balanced sets is created and used to later train any classifier.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example, we show how BalancedBaggingClassifier can be used to create a large variety of...">

.. only:: html

 .. figure:: /auto_examples/ensemble/images/thumb/sphx_glr_plot_bagging_classifier_thumb.png
     :alt: Bagging classifiers using sampler

     :ref:`sphx_glr_auto_examples_ensemble_plot_bagging_classifier.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/ensemble/plot_bagging_classifier

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Ensemble classifiers have shown to improve classification performance compare to single learner...">

.. only:: html

 .. figure:: /auto_examples/ensemble/images/thumb/sphx_glr_plot_comparison_ensemble_classifier_thumb.png
     :alt: Compare ensemble classifiers using resampling

     :ref:`sphx_glr_auto_examples_ensemble_plot_comparison_ensemble_classifier.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/ensemble/plot_comparison_ensemble_classifier
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_evaluation:

.. _evaluation_examples:

Evaluation examples
-------------------

Examples illustrating how classification using imbalanced dataset can be done.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Specific metrics have been developed to evaluate classifier which has been trained using imbala...">

.. only:: html

 .. figure:: /auto_examples/evaluation/images/thumb/sphx_glr_plot_classification_report_thumb.png
     :alt: Evaluate classification by compiling a report

     :ref:`sphx_glr_auto_examples_evaluation_plot_classification_report.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/evaluation/plot_classification_report

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Specific metrics have been developed to evaluate classifier which has been trained using imbala...">

.. only:: html

 .. figure:: /auto_examples/evaluation/images/thumb/sphx_glr_plot_metrics_thumb.png
     :alt: Metrics specific to imbalanced learning

     :ref:`sphx_glr_auto_examples_evaluation_plot_metrics.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/evaluation/plot_metrics
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_model_selection:

.. _model_selection_examples:

Model Selection
---------------

Examples related to the selection of balancing methods.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example the impact of the SMOTE&#x27;s k_neighbors parameter is examined. In the plot you ca...">

.. only:: html

 .. figure:: /auto_examples/model_selection/images/thumb/sphx_glr_plot_validation_curve_thumb.png
     :alt: Plotting Validation Curves

     :ref:`sphx_glr_auto_examples_model_selection_plot_validation_curve.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/model_selection/plot_validation_curve
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_over-sampling:

.. _over_sampling_examples:

Example using over-sampling class methods
=========================================

Data balancing can be performed by over-sampling such that new samples are generated in the minority class to reach a given balancing ratio.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates how a new sample is generated taking into account the neighbourhood of...">

.. only:: html

 .. figure:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_illustration_generation_sample_thumb.png
     :alt: Sample generator used in SMOTE-like samplers

     :ref:`sphx_glr_auto_examples_over-sampling_plot_illustration_generation_sample.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/over-sampling/plot_illustration_generation_sample

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the effect of the shrinkage factor used to generate the smoothed bootstrap u...">

.. only:: html

 .. figure:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_shrinkage_effect_thumb.png
     :alt: Effect of the shrinkage factor in random over-sampling

     :ref:`sphx_glr_auto_examples_over-sampling_plot_shrinkage_effect.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/over-sampling/plot_shrinkage_effect

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The following example attends to make a qualitative comparison between the different over-sampl...">

.. only:: html

 .. figure:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_comparison_over_sampling_thumb.png
     :alt: Compare over-sampling samplers

     :ref:`sphx_glr_auto_examples_over-sampling_plot_comparison_over_sampling.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/over-sampling/plot_comparison_over_sampling
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_pipeline:

.. _pipeline_examples:

Pipeline examples
=================

Example of how to use the a pipeline to include under-sampling with `scikit-learn` estimators.


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="An example of the :class:~imblearn.pipeline.Pipeline` object (or make_pipeline helper function)...">

.. only:: html

 .. figure:: /auto_examples/pipeline/images/thumb/sphx_glr_plot_pipeline_classification_thumb.png
     :alt: Usage of pipeline embedding samplers

     :ref:`sphx_glr_auto_examples_pipeline_plot_pipeline_classification.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/pipeline/plot_pipeline_classification
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. _sphx_glr_auto_examples_under-sampling:

.. _under_sampling_examples:

Example using under-sampling class methods
==========================================

Under-sampling refers to the process of reducing the number of samples in the majority classes.
The implemented methods can be categorized into 2 groups: (i) fixed under-sampling and (ii) cleaning under-sampling.



.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates what is a Tomek link.">

.. only:: html

 .. figure:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_illustration_tomek_links_thumb.png
     :alt: Illustration of the definition of a Tomek link

     :ref:`sphx_glr_auto_examples_under-sampling_plot_illustration_tomek_links.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/under-sampling/plot_illustration_tomek_links

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the different way of selecting example in NearMiss.">

.. only:: html

 .. figure:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_illustration_nearmiss_thumb.png
     :alt: Sample selection in NearMiss

     :ref:`sphx_glr_auto_examples_under-sampling_plot_illustration_nearmiss.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/under-sampling/plot_illustration_nearmiss

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The following example attends to make a qualitative comparison between the different under-samp...">

.. only:: html

 .. figure:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_comparison_under_sampling_thumb.png
     :alt: Compare under-sampling samplers

     :ref:`sphx_glr_auto_examples_under-sampling_plot_comparison_under_sampling.py`

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/under-sampling/plot_comparison_under_sampling
.. raw:: html

    <div class="sphx-glr-clear"></div>



.. only :: html

 .. container:: sphx-glr-footer
    :class: sphx-glr-footer-gallery


  .. container:: sphx-glr-download sphx-glr-download-python

    :download:`Download all examples in Python source code: auto_examples_python.zip </auto_examples/auto_examples_python.zip>`



  .. container:: sphx-glr-download sphx-glr-download-jupyter

    :download:`Download all examples in Jupyter notebooks: auto_examples_jupyter.zip </auto_examples/auto_examples_jupyter.zip>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.github.io>`_
