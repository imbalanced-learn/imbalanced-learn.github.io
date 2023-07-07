:orphan:

.. _general_examples:

Examples
--------

General-purpose and introductory examples for the `imbalanced-learn` toolbox.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    </div>


Examples showing API imbalanced-learn usage
-------------------------------------------

Examples that show some details regarding the API of imbalanced-learn.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the different usage of the parameter sampling_strategy for the different fam...">

.. only:: html

  .. image:: /auto_examples/api/images/thumb/sphx_glr_plot_sampling_strategy_usage_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_api_plot_sampling_strategy_usage.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">How to use sampling_strategy in imbalanced-learn</div>
    </div>


.. raw:: html

    </div>


Examples based on real world datasets
-------------------------------------

Examples which use real-word dataset.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Some balancing methods allow for balancing dataset with multiples classes. We provide an exampl...">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_plot_multi_class_under_sampling_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_plot_multi_class_under_sampling.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Multiclass classification with under-sampling</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows how to balance the text data before to train a classifier.">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_plot_topic_classication_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_plot_topic_classication.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Example of topic classification in text documents</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the use of a custom sampler to implement an outlier rejections estimat...">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_plot_outlier_rejections_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_plot_outlier_rejections.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Customized sampler to implement an outlier rejections estimator</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this face recognition example two faces are used from the LFW (Faces in the Wild) dataset. S...">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_plot_over_sampling_benchmark_lfw_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_plot_over_sampling_benchmark_lfw.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Benchmark over-sampling methods in a face recognition task</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example compares two strategies to train a neural-network on the Porto Seguro Kaggle data ...">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_porto_seguro_keras_under_sampling_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_porto_seguro_keras_under_sampling.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Porto Seguro: balancing samples in mini-batches with Keras</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the problem induced by learning on datasets having imbalanced classes....">

.. only:: html

  .. image:: /auto_examples/applications/images/thumb/sphx_glr_plot_impact_imbalanced_classes_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_applications_plot_impact_imbalanced_classes.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Fitting model on imbalanced datasets and how to fight bias</div>
    </div>


.. raw:: html

    </div>


Examples using combine class methods
====================================

Combine methods mixed over- and under-sampling methods. Generally SMOTE is used for over-sampling while some cleaning methods (i.e., ENN and Tomek links) are used to under-sample.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the effect of applying an under-sampling algorithms after SMOTE over-samplin...">

.. only:: html

  .. image:: /auto_examples/combine/images/thumb/sphx_glr_plot_comparison_combine_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_combine_plot_comparison_combine.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Compare sampler combining over- and under-sampling</div>
    </div>


.. raw:: html

    </div>


Dataset examples
-----------------------

Examples concerning the :mod:`imblearn.datasets` module.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="An illustration of the make_imbalance function to create an imbalanced dataset from a balanced ...">

.. only:: html

  .. image:: /auto_examples/datasets/images/thumb/sphx_glr_plot_make_imbalance_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_datasets_plot_make_imbalance.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Create an imbalanced dataset</div>
    </div>


.. raw:: html

    </div>


Example using ensemble class methods
====================================

Under-sampling methods implies that samples of the majority class are lost during the balancing procedure.
Ensemble methods offer an alternative to use most of the samples.
In fact, an ensemble of balanced sets is created and used to later train any classifier.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example, we show how BalancedBaggingClassifier can be used to create a large variety of...">

.. only:: html

  .. image:: /auto_examples/ensemble/images/thumb/sphx_glr_plot_bagging_classifier_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_ensemble_plot_bagging_classifier.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Bagging classifiers using sampler</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Ensemble classifiers have shown to improve classification performance compare to single learner...">

.. only:: html

  .. image:: /auto_examples/ensemble/images/thumb/sphx_glr_plot_comparison_ensemble_classifier_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_ensemble_plot_comparison_ensemble_classifier.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Compare ensemble classifiers using resampling</div>
    </div>


.. raw:: html

    </div>


Evaluation examples
-------------------

Examples illustrating how classification using imbalanced dataset can be done.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Specific metrics have been developed to evaluate classifier which has been trained using imbala...">

.. only:: html

  .. image:: /auto_examples/evaluation/images/thumb/sphx_glr_plot_classification_report_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_evaluation_plot_classification_report.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Evaluate classification by compiling a report</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Specific metrics have been developed to evaluate classifier which has been trained using imbala...">

.. only:: html

  .. image:: /auto_examples/evaluation/images/thumb/sphx_glr_plot_metrics_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_evaluation_plot_metrics.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Metrics specific to imbalanced learning</div>
    </div>


.. raw:: html

    </div>


Model Selection
---------------

Examples related to the selection of balancing methods.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example the impact of the SMOTE&#x27;s k_neighbors parameter is examined. In the plot you ca...">

.. only:: html

  .. image:: /auto_examples/model_selection/images/thumb/sphx_glr_plot_validation_curve_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_model_selection_plot_validation_curve.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Plotting Validation Curves</div>
    </div>


.. raw:: html

    </div>


Example using over-sampling class methods
=========================================

Data balancing can be performed by over-sampling such that new samples are generated in the minority class to reach a given balancing ratio.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates how a new sample is generated taking into account the neighbourhood of...">

.. only:: html

  .. image:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_illustration_generation_sample_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_over-sampling_plot_illustration_generation_sample.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Sample generator used in SMOTE-like samplers</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows the effect of the shrinkage factor used to generate the smoothed bootstrap u...">

.. only:: html

  .. image:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_shrinkage_effect_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_over-sampling_plot_shrinkage_effect.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Effect of the shrinkage factor in random over-sampling</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The following example attends to make a qualitative comparison between the different over-sampl...">

.. only:: html

  .. image:: /auto_examples/over-sampling/images/thumb/sphx_glr_plot_comparison_over_sampling_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_over-sampling_plot_comparison_over_sampling.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Compare over-sampling samplers</div>
    </div>


.. raw:: html

    </div>


Pipeline examples
=================

Example of how to use the a pipeline to include under-sampling with `scikit-learn` estimators.


.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="An example of the :class:~imblearn.pipeline.Pipeline` object (or make_pipeline helper function)...">

.. only:: html

  .. image:: /auto_examples/pipeline/images/thumb/sphx_glr_plot_pipeline_classification_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_pipeline_plot_pipeline_classification.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Usage of pipeline embedding samplers</div>
    </div>


.. raw:: html

    </div>


Example using under-sampling class methods
==========================================

Under-sampling refers to the process of reducing the number of samples in the majority classes.
The implemented methods can be categorized into 2 groups: (i) fixed under-sampling and (ii) cleaning under-sampling.



.. raw:: html

    <div class="sphx-glr-thumbnails">


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates what is a Tomek link.">

.. only:: html

  .. image:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_illustration_tomek_links_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_under-sampling_plot_illustration_tomek_links.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Illustration of the definition of a Tomek link</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the different way of selecting example in NearMiss.">

.. only:: html

  .. image:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_illustration_nearmiss_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_under-sampling_plot_illustration_nearmiss.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Sample selection in NearMiss</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The following example attends to make a qualitative comparison between the different under-samp...">

.. only:: html

  .. image:: /auto_examples/under-sampling/images/thumb/sphx_glr_plot_comparison_under_sampling_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_under-sampling_plot_comparison_under_sampling.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Compare under-sampling samplers</div>
    </div>


.. raw:: html

    </div>


.. toctree::
   :hidden:
   :includehidden:


   /auto_examples/api/index.rst
   /auto_examples/applications/index.rst
   /auto_examples/combine/index.rst
   /auto_examples/datasets/index.rst
   /auto_examples/ensemble/index.rst
   /auto_examples/evaluation/index.rst
   /auto_examples/model_selection/index.rst
   /auto_examples/over-sampling/index.rst
   /auto_examples/pipeline/index.rst
   /auto_examples/under-sampling/index.rst


.. only:: html

  .. container:: sphx-glr-footer sphx-glr-footer-gallery

    .. container:: sphx-glr-download sphx-glr-download-python

      :download:`Download all examples in Python source code: auto_examples_python.zip </auto_examples/auto_examples_python.zip>`

    .. container:: sphx-glr-download sphx-glr-download-jupyter

      :download:`Download all examples in Jupyter notebooks: auto_examples_jupyter.zip </auto_examples/auto_examples_jupyter.zip>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.github.io>`_
